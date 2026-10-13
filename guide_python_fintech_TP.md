# Python pour la fintech : guide des TP 01 et TP 02

> Fiche de révision basée sur `TP_01_Calcul.ipynb` et `TP_02_Rendements_Graphiques.ipynb`.
> Objectif : comprendre **à quoi sert chaque code**, **quoi retenir par cœur**, et **où ça sert en finance** (risque de crédit, marchés, analyse financière).

---

## 0. Vue d'ensemble : pourquoi ces TP ?

En fintech, on ne travaille plus seulement sur Excel. On automatise des calculs financiers avec Python. Ces deux TP couvrent les **5 briques de base** :

| Brique | Ce que tu apprends | Usage fintech |
|---|---|---|
| 1. Rendements | Passer d'une série de prix à des rendements | Analyse de performance, risque de marché |
| 2. Calcul vectorisé (NumPy) | Calculer sur toute une série sans boucle | Rapidité, backtesting, simulations |
| 3. Rendement composé | Valeur future, rendement cumulé vs moyenne | Placement, capitalisation, performance d'un portefeuille |
| 4. Condition + boucle | Règle de décision appliquée à chaque dossier | Scoring crédit, alertes, filtrage de dossiers |
| 5. DataFrame (pandas) | Un tableau de clients avec colonnes calculées | Taux d'endettement, ratios financiers, bases de données |
| 6. Données de marché + graphiques (TP 02) | Télécharger un cours de bourse, calculer les log-rendements, tracer | Volatilité, VaR, modèles de risque |

**Ce que le prof attend vraiment** : que tu saches lire un code, l'interpréter financièrement, et le réécrire seule sur un cas simple. Pas de mémoriser la syntaxe de matplotlib au caractère près.

---

## 1. Les imports (à connaître par cœur)

```python
import numpy as np
import pandas as pd
import yfinance as yf
import matplotlib.pyplot as plt
```

| Bibliothèque | Alias | Rôle |
|---|---|---|
| NumPy | `np` | Calcul numérique sur tableaux (moyenne, produit, log, etc.) |
| pandas | `pd` | Tableaux de données (DataFrame, Series), séries temporelles |
| yfinance | `yf` | Télécharger des cours boursiers (Yahoo Finance) |
| matplotlib | `plt` | Tracer des graphiques |

**À retenir** : sans `import numpy as np`, tu obtiens `NameError: name 'np' is not defined`. C'est l'erreur que tu as eue dans ton test `assert np.isclose(...)` : l'import manquait.

---

## 2. Rendement simple avec `pct_change()`

```python
prix = pd.Series([100, 102, 101, 104])
rendements = prix.pct_change(fill_method=None)
print(rendements.dropna())
```

### Formule (à savoir par cœur)

$$R_t = \frac{P_t - P_{t-1}}{P_{t-1}} = \frac{P_t}{P_{t-1}} - 1$$

### Résultat

| t | Prix | Calcul | Rendement |
|---|---|---|---|
| 0 | 100 | (pas de prix précédent) | NaN |
| 1 | 102 | 102/100 − 1 | +2,00 % |
| 2 | 101 | 101/102 − 1 | −0,98 % |
| 3 | 104 | 104/101 − 1 | +2,97 % |

### Explication ligne par ligne

- `pd.Series([...])` : une série de valeurs indexées (ici, des prix).
- `.pct_change()` : calcule automatiquement le rendement simple entre chaque période et la précédente.
- `fill_method=None` : demande de ne pas combler les valeurs manquantes (bonne pratique, évite un avertissement dans les versions récentes de pandas).
- `.dropna()` : supprime le premier NaN (il n'y a pas de rendement pour la première date).

### Usage fintech
Tout part des rendements : volatilité, corrélation, ratio de Sharpe, VaR. Les prix bruts ne sont presque jamais utilisés directement dans les modèles.

---

## 3. Calcul vectorisé avec NumPy

```python
r = np.array([0.02, -0.01, 0.03])
print(round(r.mean(), 3))               # 0.013
print(round(np.prod(1 + r) - 1, 3))     # 0.04
```

### Idée centrale
**Vectorisé = on applique une opération à tout le tableau d'un coup, sans écrire de boucle `for`.** C'est plus court, plus lisible et beaucoup plus rapide sur des millions de lignes (par exemple 10 ans de cours journaliers).

### Les deux formules à connaître

| Calcul | Code | Formule | Résultat |
|---|---|---|---|
| Moyenne arithmétique des rendements | `r.mean()` | (r₁ + r₂ + r₃) / 3 | 1,33 % |
| Rendement cumulé | `np.prod(1 + r) - 1` | (1+r₁)(1+r₂)(1+r₃) − 1 | 4,01 % |

### Le piège classique (très demandé à l'oral)
**La moyenne des rendements n'est pas le rendement cumulé divisé par n.**
- Moyenne arithmétique : 1,33 % par période.
- Si tu additionnes naïvement 3 × 1,33 % = 4,00 %, tu obtiens presque, mais pas exactement, le vrai cumul de 4,0094 %.
- Le vrai rendement cumulé tient compte de l'**effet de composition** : chaque rendement s'applique sur un capital déjà modifié.
- Le rendement moyen « composé » (moyenne géométrique) est : (1,040094)^(1/3) − 1 ≈ **1,32 %**.

### Note sur l'exemple du TP 02
Dans le TP 02, `r = np.array([0.02, 0.02, 0.02])` donne une moyenne de 2 % et un cumul de 6,1 % (1,02³ − 1 = 0,061208). Quand tous les rendements sont identiques, moyenne géométrique et arithmétique coïncident ; c'est le cas simple pour vérifier que tu as compris.

---

## 4. Rendement composé et fonction `valeur_future`

```python
def valeur_future(c, r, n):
    """
    c : present value
    r : interest rate
    n : number of periods
    """
    return c * (1 + r) ** n

print("Valeur future :", round(valeur_future(100, 0.05, 2), 2))   # 110.25
```

### Formule (à savoir par cœur, c'est LA formule de base)

$$VF = C \times (1 + r)^n$$

### Calcul à la main
100 × 1,05² = 100 × 1,1025 = **110,25**

### Vocabulaire de la fonction Python

| Élément | Signification |
|---|---|
| `def` | Définir une fonction réutilisable |
| `c, r, n` | Paramètres : capital, taux, nombre de périodes |
| `return` | Renvoie le résultat |
| `"""docstring"""` | Texte qui documente la fonction (bonne pratique professionnelle) |
| `**` | Puissance en Python (pas `^` !) |

### Usage fintech
- Capitalisation d'un placement ou d'un dépôt.
- Base de l'**actualisation** (VAN, TIR, coût du capital) : l'actualisation est l'opération inverse, VA = VF / (1+r)ⁿ.
- Une fonction écrite une fois peut être réutilisée dans tous tes projets (c'est la logique d'un « module de calcul » dans une plateforme fintech).

---

## 5. `assert` : vérifier que ton calcul est juste

```python
assert np.isclose(valeur_future(1000, 0.05, 2), 1102.5)
assert np.isclose(np.prod(1 + r) - 1, 0.040094)
```

### À quoi ça sert
`assert condition` vérifie qu'une condition est vraie.
- Condition vraie : **rien ne s'affiche** (c'est bon signe).
- Condition fausse : Python lève une `AssertionError` et le programme s'arrête.

### Pourquoi `np.isclose` et pas `==` ?
Les ordinateurs stockent les nombres décimaux de façon approchée. Exemple : `0.1 + 0.2 == 0.3` donne `False` en Python. `np.isclose` compare avec une petite tolérance, ce qui est indispensable pour des calculs financiers avec décimales.

### Usage fintech
C'est la base des **tests unitaires** : avant de mettre un modèle de calcul en production, on vérifie qu'il donne les valeurs attendues sur des cas connus. Une erreur de formule sur un taux ou un rendement peut avoir un impact financier réel.

---

## 6. Condition et boucle : règle de décision de crédit

```python
scores = [0.02, 0.15, 0.35]
for probabilite in scores:
    if probabilite >= 0.20:
        print("Refuser")
    else:
        print("Accorder")
```

### Lecture financière
`scores` = probabilités de défaut (PD) estimées pour 3 clients. Le seuil de 20 % est une **hypothèse** simplifiée.

| Client | PD | Décision |
|---|---|---|
| 1 | 2 % | Accorder |
| 2 | 15 % | Accorder |
| 3 | 35 % | Refuser |

### Structure à connaître par cœur

```python
for element in liste:        # parcourt chaque élément
    if condition:            # teste une règle
        ...                  # action si vrai
    else:
        ...                  # action sinon
```

Attention à l'**indentation** (4 espaces) : en Python, elle fait partie de la syntaxe.

### Lien avec ta spécialisation (risque de crédit)
- **PD** (probabilité de défaut) : concept central en Bâle III et IFRS 9.
- Dans la réalité, la décision ne dépend pas que de la PD : politique de risque, revenus, endettement, garanties, **LGD** (perte en cas de défaut) et **EAD** (exposition au défaut). La perte attendue se calcule : **EL = PD × LGD × EAD**.
- Le texte du TP parle d'une « revue humaine » : dans un vrai dispositif, un refus automatique n'est pas toujours acceptable, des cas limites sont envoyés à un analyste.

### Amélioration possible (3 zones plutôt que 2)

```python
for p in scores:
    if p >= 0.20:
        print("Refuser")
    elif p >= 0.10:
        print("Revue humaine")
    else:
        print("Accorder")
```

---

## 7. DataFrame pandas : tableau de clients et taux d'endettement

```python
clients = pd.DataFrame({
    "client": [1, 2, 3],
    "revenu_mensuel": [2000, 3000, 5000],
    "mensualite_dette": [400, 1200, 750]
})
clients["ratio"] = clients["mensualite_dette"] / clients["revenu_mensuel"]
print(clients)
```

### Résultat

| client | revenu_mensuel | mensualite_dette | ratio |
|---|---|---|---|
| 1 | 2 000 | 400 | 0,20 (20 %) |
| 2 | 3 000 | 1 200 | 0,40 (40 %) |
| 3 | 5 000 | 750 | 0,15 (15 %) |

### Formule (à savoir par cœur)

$$\text{Taux d'endettement} = \frac{\text{Mensualités de dettes}}{\text{Revenu mensuel}}$$

### Concepts pandas à retenir

| Concept | Définition |
|---|---|
| **DataFrame** | Tableau avec colonnes nommées et index (comme une feuille Excel) |
| **Series** | Une seule colonne, c'est-à-dire des valeurs indexées |
| `df["col"]` | Sélectionner une colonne |
| `df["nouvelle"] = ...` | Créer une colonne calculée, appliquée automatiquement à toutes les lignes |

### Interprétation
Le client 2 consacre 40 % de son revenu au remboursement de ses dettes. Beaucoup de banques fixent un plafond d'endettement autour d'un tiers du revenu (le seuil exact dépend de la banque, du pays et du profil client), donc ce dossier serait en zone de vigilance.

### Pour avoir directement des pourcentages

```python
clients["taux_endettement"] = clients["mensualite_dette"] / clients["revenu_mensuel"] * 100
```

### Combiner les sections 6 et 7 (exercice type d'examen)

```python
clients["decision"] = clients["ratio"].apply(lambda x: "Refuser" if x >= 0.35 else "Accorder")
```

---

## 8. TP 02 : données de marché et log-rendements

### 8.1 Télécharger les cours

```python
ticker = yf.Ticker('GOOGL')
data = ticker.history(period="10y")
data.head()
data.tail()
```

| Code | Rôle |
|---|---|
| `yf.Ticker('GOOGL')` | Crée un objet lié à l'action Alphabet (classe A) |
| `.history(period="10y")` | Télécharge 10 ans d'historique journalier : Open, High, Low, Close, Volume, etc. |
| `data.head()` / `data.tail()` | Affiche les 5 premières / dernières lignes pour vérifier |

**Point important pour ton domaine** : par défaut, les prix `Close` de yfinance sont **ajustés** des splits et des dividendes. C'est pour cela qu'un stock split (comme celui de Managem, division par 10) ne crée pas de « faux crash » de 90 % dans les rendements calculés. Sans ajustement, un split ferait apparaître une chute artificielle du cours alors que la richesse de l'actionnaire n'a pas changé.

### 8.2 Tracer le cours

```python
fig, ax = plt.subplots(figsize=(12, 6), nrows=1, ncols=1, facecolor="#F0F0F0")
plt.plot(data['Close'])
plt.title("Daily Alphabet Inc Class A (GOOGL) for last 10 years", fontsize=20)
plt.show()
```

- `plt.subplots(...)` : crée la figure (taille, fond gris clair).
- `plt.plot(data['Close'])` : trace le cours de clôture dans le temps.
- `plt.title(...)` : titre. `plt.show()` : affiche.

### 8.3 Log-rendement (rendement géométrique)

```python
returns = np.log(data[['Close']] / data[['Close']].shift(1))
returns = returns[1:]
```

### Formule (à savoir par cœur)

$$r_t = \ln\left(\frac{P_t}{P_{t-1}}\right)$$

| Code | Rôle |
|---|---|
| `.shift(1)` | Décale la série d'un jour : donne le prix de la veille |
| `P_t / P_{t-1}` | Rapport prix du jour / prix de la veille |
| `np.log(...)` | Logarithme népérien |
| `returns[1:]` | Supprime la première ligne (NaN, pas de veille) |

### Pourquoi les log-rendements ? (question classique)

| Propriété | Explication |
|---|---|
| **Additifs dans le temps** | Le log-rendement sur 10 jours = somme des 10 log-rendements journaliers. Avec les rendements simples, il faut multiplier. |
| **Symétriques** | +10 % puis −10 % en log s'annulent exactement, pas en rendement simple. |
| **Proches des rendements simples** | Pour de petites variations (quelques %), les deux sont presque identiques. |
| **Hypothèse des modèles** | Black-Scholes et beaucoup de modèles de risque supposent des log-rendements normaux. |

Lien entre les deux : r_log = ln(1 + R_simple).

### 8.4 Tracer les log-rendements (volatilité visuelle)

```python
fig, ax = plt.subplots(figsize=(14, 8), nrows=1, ncols=1, facecolor="#F0F0F0")
for i in returns.columns.values:
    plt.plot(returns.index, returns[i], lw=2, alpha=0.8, label=i)
plt.legend(loc="lower center", fontsize=14)
plt.ylabel("daily log returns")
```

- La boucle `for` parcourt les colonnes (ici une seule : `Close`) : le code est écrit pour fonctionner avec **plusieurs actions** à la fois.
- `lw` = épaisseur de ligne, `alpha` = transparence, `label` = nom dans la légende.

### Comment lire ce graphique
- Les rendements oscillent autour de 0.
- Les **pics** correspondent à des chocs (par exemple mars 2020, Covid).
- Les périodes où les barres sont larges = **forte volatilité** ; les **clusters de volatilité** (les périodes agitées se regroupent) sont un fait stylisé central en finance de marché.

### Pour aller plus loin (mesurer la volatilité)

```python
vol_journaliere = returns['Close'].std()
vol_annuelle = vol_journaliere * np.sqrt(252)   # 252 jours de bourse par an
```

---

## 9. Ce qu'il faut savoir PAR CŒUR (checklist)

### Formules

| # | Formule | Nom |
|---|---|---|
| 1 | R = P_t / P_{t-1} − 1 | Rendement simple |
| 2 | r = ln(P_t / P_{t-1}) | Log-rendement |
| 3 | R_cumulé = ∏(1 + R_i) − 1 | Rendement cumulé |
| 4 | VF = C × (1 + r)ⁿ | Valeur future |
| 5 | Taux d'endettement = mensualités / revenus | Ratio d'endettement |
| 6 | EL = PD × LGD × EAD | Perte attendue (lien risque de crédit) |
| 7 | σ_annuelle = σ_jour × √252 | Annualisation de la volatilité |

### Syntaxe Python

| Syntaxe | Sert à |
|---|---|
| `import numpy as np` / `import pandas as pd` | Charger les bibliothèques |
| `pd.Series`, `pd.DataFrame` | Créer séries et tableaux |
| `.pct_change()`, `.shift(1)` | Rendements, décalage temporel |
| `.mean()`, `.std()`, `np.prod()` | Statistiques et produit |
| `df["col"] = ...` | Ajouter une colonne calculée |
| `for ... in ...:` / `if ... else:` | Boucle et condition |
| `def f(...): return ...` | Fonction |
| `assert np.isclose(a, b)` | Test de vérification |
| `plt.plot()`, `plt.show()` | Graphique |

### Idées à pouvoir expliquer à l'oral
1. Pourquoi moyenne des rendements ≠ rendement cumulé ?
2. Pourquoi utiliser les log-rendements ?
3. Pourquoi `np.isclose` plutôt que `==` ?
4. Pourquoi le seuil de 20 % est-il « une hypothèse » et pas une règle universelle ?
5. Pourquoi un split ne change-t-il pas la richesse de l'actionnaire ?

---

## 10. Erreurs fréquentes à éviter

| Erreur | Cause | Correction |
|---|---|---|
| `NameError: name 'np' is not defined` | Import oublié ou noyau redémarré | Exécuter la cellule d'import d'abord |
| `r ^ 2` au lieu de `r ** 2` | `^` n'est pas la puissance en Python | Utiliser `**` |
| Exécuter les cellules dans le désordre | Variables non définies | « Restart & Run All » dans Jupyter |
| Oublier l'indentation après `if` / `for` | Syntaxe Python | 4 espaces |
| Confondre prix et rendements | Modèles appliqués aux prix bruts | Toujours convertir en rendements d'abord |
| Pourcentage vs décimal (0,20 vs 20) | Mélange d'unités | Garder des décimales dans les calculs, multiplier par 100 à l'affichage |
| Oublier `dropna()` ou `[1:]` | Le premier rendement est NaN | Supprimer la première ligne |

---

## 11. Remarques sur tes notebooks (pour les nettoyer)

- Le TP 02 commence par le titre « TP 01 » : à renommer en « TP 02 ».
- Quelques fautes de frappe dans les titres de cellules (« Compue Geomeric » devrait être « Compute Geometric », « illustre » devrait être « illustrate »).
- La numérotation des sections est désordonnée (1, puis 3, puis 4, puis 2…) : à remettre dans l'ordre.
- Les sections 2 à 5 du TP 02 reprennent celles du TP 01 : ce n'est pas un problème, mais tu peux les laisser dans un seul des deux notebooks.
- Pour ton portfolio : ajoute une cellule markdown d'**interprétation financière** après chaque graphique. C'est ce qui distingue un notebook d'étudiante en finance d'un simple exercice de code.

---

## 12. Mini-exercices pour t'entraîner (sans regarder le cours)

1. Calcule à la main puis avec Python la valeur future de 5 000 DH à 4 % pendant 3 ans.
2. Prix : 50, 55, 49,5, 52. Calcule les rendements simples puis les log-rendements. Compare.
3. Crée un DataFrame de 4 clients avec revenu, mensualité, et ajoute `ratio` et une colonne `decision` (refuser si ratio ≥ 0,35).
4. Télécharge l'historique d'une autre action avec `yfinance` et calcule sa volatilité annualisée.
5. Écris un `assert` qui vérifie que ta fonction `valeur_future(200, 0.10, 2)` renvoie 242.

---

**En une phrase** : ces TP t'apprennent à transformer des **prix en rendements**, des **rendements en indicateurs de risque**, et des **données clients en décisions**, avec Python plutôt qu'Excel, ce qui est la base du travail d'un analyste risque en fintech.
