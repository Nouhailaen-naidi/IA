# Chapitre 1 — Le coût du capital

> **Source principale (cours du professeur) :** Prof. Hicham MEGHOUAR, ENCG-Settat, pages 1 à 15 (photographies).
> **Source complémentaire :** A. Boughaba, *Cours d'analyse et d'évaluation de projets* (Éditions Berti, PDF de 304 p.).
> **Légende :**
> - **[Cours]** = contenu des photos du professeur.
> - **[Complément]** = contenu du PDF.
> - **[Application]** = mise en pratique chiffrée.
> - **[À vérifier]** = ambiguïté, erreur apparente ou hypothèse que j'ai dû faire.
>
> Les pages sont citées « p. X du cours » (numéro imprimé en bas de page).

---

## 1. Présentation du chapitre

**Intitulé :** Chapitre 1 — Le coût du capital (p. 1 du cours).

**Plan réel du professeur :**

1. Le coût du capital : le concept général
2. Évaluation du coût du capital
   - 2.1 Évaluation du coût des fonds propres
     - 2.1.1 Modèles fondés sur l'actualisation des revenus des fonds propres
       - 2.1.1.1 Modèle d'actualisation des dividendes (Irving Fisher ; Gordon-Shapiro)
       - 2.1.1.2 Modèle d'actualisation des bénéfices nets (inverse du PER ; Charreaux)
     - 2.1.2 Estimation par le MEDAF (définition ; décomposition de la prime de risque)
   - 2.2 Évaluation des coûts de financement par emprunt et par crédit-bail
     - 2.2.1 Évaluation du coût de la dette (taux actuariel ; amortissement d'un emprunt)
     - 2.2.2 Évaluation du coût du crédit-bail
3. Le coût moyen pondéré du capital (CMPC)

> **[À vérifier]** Sur la page 14 le titre est numéroté « 2. LE COUT MOYEN PONDERE DU CAPITAL ». Je le traite comme la partie finale du chapitre, à la suite de la partie 2.

**Objectifs pédagogiques :**

- Définir le coût du capital et savoir à quoi il sert.
- Estimer le coût des fonds propres par trois approches : dividendes, bénéfices, MEDAF.
- Estimer le coût de la dette (taux actuariel après impôt) et celui du crédit-bail.
- Agréger le tout dans le CMPC.

**Compétences de calcul à maîtriser :**

- Gordon-Shapiro (\( k = D_1/P_0 + g \)) et \( r = B/P_0 \).
- MEDAF et décomposition du bêta.
- Tableau d'amortissement (trois modes de remboursement).
- Taux actuariel avec ou sans fiscalité, avec frais.
- CMPC avec pondérations en valeur de marché.

**Enchaînement logique :**

```
Fonds propres (k_e) ─┐
                     ├──► CMPC (taux d'actualisation, DCF, VAN) 
Dette (k_d après IS) ─┘
Crédit-bail = substitut à l'emprunt (coût = taux actuariel du bailleur)
```

---

## 2. Cours théorique complet

### 2.0. Introduction et concept général du coût du capital (p. 1–2)

**[Cours] Importance.** La détermination du coût du capital (aussi appelé *coût moyen pondéré du capital*) n'est pas toujours simple mais elle est fondamentale. Il sert :

- au choix d'investissement : c'est le taux d'actualisation de la VAN, ou le taux auquel on compare le TRI ;
- à la détermination de la valeur de l'actif économique.

**Attention à la confusion :** le *coût du capital* (coût moyen pondéré des capitaux apportés à l'entreprise) n'est **pas** le *coût des capitaux propres*, qui n'en est qu'une composante.

**[Cours] Contexte historique.** Les notions de coût du capital et de structure financière optimale ont attiré le développement théorique en finance d'entreprise sur la période 1960-1980. Les premiers à en avoir traité spécifiquement sont **F. Modigliani et M. Miller** (article de 1958). Leurs thèses ont fortement marqué la finance, bien qu'elles ne soient pas toujours partagées et aient elles-mêmes évolué.

**Définition [Cours].** Le coût du capital est le **taux de rentabilité minimum** que doivent dégager les investissements de l'entreprise pour satisfaire à la fois :

- l'exigence de rentabilité des **actionnaires** (coût des capitaux propres) ;
- l'exigence de rentabilité des **créanciers** (coût de l'endettement net).

C'est donc le coût de financement global de l'entreprise (le professeur cite Vernimmen).

> **[À vérifier]** La référence est écrite « Vernimmen, 2026 » sur la photo. Je la reproduis telle quelle, sans pouvoir la confirmer.

**Logique financière.** Déterminer le coût du capital impose :

1. de calculer le **coût spécifique** de chaque source de financement ;
2. de mesurer le **poids** de chacune dans le financement global.

**Trois usages principaux [Cours] :**

1. Taux de rendement minimal de référence auquel on compare le TRI des projets (évaluation de projets).
2. Choix de la **structure du capital optimale**, celle qui minimise le CMPC.
3. Fixation des prix dans les **secteurs réglementés** (exemple du professeur : l'hydroélectricité), où le CMPC du monopole est considéré comme un juste taux de rendement.

---

### 2.1. Évaluation du coût des fonds propres (p. 2)

**Définition [Cours].** Le coût des fonds propres résulte de l'**exigence de rémunération exprimée par les actionnaires**, ou du taux de rémunération servi aux actionnaires pour maintenir leur satisfaction à l'égard des titres détenus.

**Différences avec la dette (explication de la page 2) :**

| Critère | Rémunération des actionnaires | Charges financières sur dettes |
|---|---|---|
| Nature | **Aléatoire** | **Contractuelle** |
| Fiscalité | **Non déductible** : versée après impôt sur le résultat | Déductible |

**Influence du risque.** Le taux de rentabilité requis dépend du niveau de risque du titre. Plus le **risque d'exploitation** et le **risque financier** sont élevés, plus la **prime de risque** est élevée et plus le **coût des fonds propres augmente**.

**Approximation par les dividendes.** Les dividendes à payer donnent une approximation du coût du capital. Les actionnaires sont vus comme des apporteurs de capitaux **non remboursés**, en dehors de la rémunération permanente par les dividendes. Le coût des capitaux apportés est le **taux d'actualisation qui égalise la somme des entrées et des sorties de trésorerie pour l'actionnaire**.

---

### 2.1.1. Modèles fondés sur l'actualisation des revenus des fonds propres (p. 2)

Les modèles théoriques d'évaluation du coût des fonds propres fondés sur l'actualisation des flux de **dividendes** ou de **bénéfices** s'inscrivent dans le cadre d'une **hypothèse de risque donnée**.

---

#### 2.1.1.1. Le modèle d'actualisation des dividendes

##### 1.1 Le modèle d'Irving Fisher (p. 2–3)

**Définition.** À l'équilibre, le cours de l'action est égal à la valeur actuelle des dividendes futurs, augmentée de la valeur de cession de l'action.

**Formule :**

$$
P_0 = \frac{D_1}{1+k} + \frac{D_2}{(1+k)^2} + \dots + \frac{D_n}{(1+k)^n} + \frac{P_n}{(1+k)^n}
$$

$$
P_0 = \sum_{i=1}^{n} D_i (1+k)^{-i} + P_n (1+k)^{-n}
$$

**Signification des variables :**

| Symbole | Signification |
|---|---|
| \( P_0 \) | Cours du titre à la date \( t_0 \) |
| \( D_i \) | Dividendes futurs (\( i = 1, 2, \dots, n \)) |
| \( P_n \) | Prix de cession du titre à la date \( n \) |
| \( k \) | Taux d'actualisation = **coût des capitaux propres** |

**Logique financière.** \( k \) est le taux qui rend le prix payé aujourd'hui égal à tout ce que l'actionnaire recevra (dividendes + prix de revente). C'est donc un **taux de rendement interne** du placement en actions.

**Cas particulier (Fisher).** Irving Fisher traite le modèle en supposant des **dividendes constants**. Comme prévoir les dividendes à l'infini est impossible, il faut poser des hypothèses. Pour un dividende constant à l'infini :

$$
P_0 = \frac{D}{k} \qquad\Longleftrightarrow\qquad k = \frac{D}{P_0}
$$

(\( D \) est une perpétuité constante.)

**Erreur à éviter :** appliquer \( P_0 = D/k \) quand les dividendes croissent. Dans ce cas on utilise Gordon-Shapiro.

##### 1.2 Le modèle de Gordon-Shapiro (p. 3–4)

**Définition.** L'hypothèse de constance des dividendes étant trop simplificatrice, Gordon et Shapiro supposent que le dividende est animé d'un **taux de croissance constant \( g \) jusqu'à l'infini**. On obtient une **suite géométrique** qui, après simplification, donne la formule suivante.

**Formule (p. 3) :**

$$
P_0 = \sum_{t=1}^{n} \frac{D_1 (1+g)^{t-1}}{(1+k)^t} = \frac{D_1}{k-g}
$$

La valeur de l'action est égale à la somme, à un horizon lointain, des dividendes distribués compte tenu de leur croissance annuelle \( g \) :

$$
P_0 = \frac{D_1}{1+k} + \frac{D_1(1+g)}{(1+k)^2} + \frac{D_1(1+g)^2}{(1+k)^3} + \dots = \frac{D_1}{k-g}\left[1-\left(\frac{1+g}{1+k}\right)^n\right]
$$

> **[À vérifier]** Sur la photo, le terme de droite est écrit « \( D_1 \frac{(1+g)^n - 1}{(1+k)^n} \) ». Sous cette forme exacte, ce n'est pas la somme de la série (le professeur a simplifié l'écriture). La conclusion qui compte est la limite quand \( n\to\infty \), ci-dessous.

**Passage à la limite.** Avec \( k > g \), lorsque \( n \) devient grand, le terme \( \left(\frac{1+g}{1+k}\right)^n \) tend vers 0, et :

$$
P_0 = \frac{D_0 (1+g)}{k-g} = \frac{D_1}{k-g}
\qquad\Longrightarrow\qquad
\boxed{\,k = \frac{D_1}{P_0} + g\,}
$$

**Variables :**

| Symbole | Signification |
|---|---|
| \( D_1 \) | Dividende anticipé en \( t=1 \) ; \( D_1 = D_0 (1+g) \) |
| \( P_0 \) | Prix de l'action en période initiale |
| \( g \) | Taux de croissance constant des dividendes |
| \( k \) | Taux de rendement requis par les actionnaires pour un niveau de risque donné = **coût du capital (propre)** |

**Conditions d'application :**

- horizon infini, croissance \( g \) constante ;
- **\( k > g \)** (sinon la formule n'a pas de sens) ;
- l'entreprise **distribue des dividendes**.

**Limites (p. 4) :** le modèle reste **simpliste** et soumis à des **hypothèses fortes** (horizon infini, régularité d'évolution des dividendes). Il n'est **pas applicable aux entreprises ne distribuant pas de dividendes**.

**Interprétation de \( k = D_1/P_0 + g \) :** le rendement exigé = rendement courant (dividend yield) + croissance attendue (plus-value).

**Erreurs à éviter :**

- Utiliser \( D_0 \) au lieu de \( D_1 \) au numérateur. Il faut d'abord calculer \( D_1 = D_0(1+g) \) si l'énoncé donne le dernier dividende versé.
- Oublier d'ajouter \( g \) à la fin.

**Exemple chiffré (inventé pour illustrer, pas dans le cours) :** \( P_0 = 100 \), \( D_0 = 5 \), \( g = 4\% \) ⇒ \( D_1 = 5{,}2 \) ⇒ \( k = 5{,}2/100 + 4\% = 9{,}2\% \).

##### Applications 1 et 2 (p. 4) — voir section 4.

---

#### 2.1.1.2. Le modèle d'actualisation des bénéfices nets (p. 5–6)

**Définition.** Plutôt que d'actualiser les dividendes, ce modèle actualise le **bénéfice net par action** requis par les actionnaires. Les bénéfices nets reflètent effectivement le potentiel de rémunération globale de l'actionnaire **cerné avant son affectation** (avant de décider ce qui est distribué ou réinvesti). Les autres hypothèses du modèle des dividendes sont maintenues : horizon lointain et bénéfice par action constant.

**Formule :**

$$
P_0 = \sum_{t=1}^{n} \frac{B_t}{(1+r)^t} = \frac{B}{r}
$$

\( B_t \) = bénéfice par action en \( t \). Quand \( n \to \infty \) et \( B \) constant : \( P_0 = B/r \), d'où

$$
\boxed{\,r = \frac{B}{P_0}\,}
$$

\( r \) est le taux de rentabilité requis par les actionnaires, qui définit le **coût des capitaux propres**. Il apparaît alors comme l'**inverse du PER** (coefficient de capitalisation des résultats) : \( r = 1/\text{PER} = B/P_0 \).

**Condition clé.** L'appréciation du coût du capital par l'inverse du PER **n'est acceptable que pour une entreprise à croissance nulle** (bénéfices constants).

**Cas de croissance (Charreaux) [Cours, p. 5–6].** Charreaux montre qu'en situation de croissance :

$$
\text{PER} = \frac{P_0}{B} = \frac{1-b}{r - b\,K}
\qquad
P_0 = \frac{B(1-b)}{r - b\,K}
\qquad
r = \frac{B(1-b)}{P_0} + b\,K
$$

| Symbole | Signification (p. 6) |
|---|---|
| \( B \) | Bénéfice par action |
| \( b \) | **Taux de réinvestissement** des bénéfices (\( b = 1-d \), \( d \) = taux de distribution) |
| \( K \) | **Taux de rentabilité comptable attendu** des fonds propres |
| \( r \) | Coût des capitaux propres (taux requis) |

**Deux cas d'exception** où \( r \) est égal à l'inverse du PER :

- **Cas 1 : \( b = 0 \)** : la totalité du bénéfice est distribuée en dividendes, sans réinvestissement ;
- **Cas 2 : \( r = K \)** : il n'y a pas d'exigence de rémunération additionnelle de la part des actionnaires (le réinvestissement rapporte exactement ce que les actionnaires exigent).

Dans les deux cas :

$$
\text{PER} = \frac{1-b}{r(1-b)} = \frac{1}{r}
\quad\Rightarrow\quad r = \frac{1}{\text{PER}} = \frac{B}{P_0}
$$

> **[À vérifier]** Sur la photo p. 6, la ligne « PER = (1−b)/(r(1−b)) = 1/r » est partiellement floue. Elle est cohérente avec la formule de Charreaux quand \( r = K \) : \( (1-b)/(r-br) = (1-b)/(r(1-b)) = 1/r \). C'est ainsi que je la lis.

**Lien avec Gordon-Shapiro (p. 6).** On sait que \( P_0 = D_1/(k-g) \). Si le taux de réinvestissement \( b \) (= \( 1-d \)) est constant, le taux de croissance des dividendes est égal au taux de croissance des bénéfices, soit :

$$
g = b \times K
$$

c'est-à-dire le taux de rentabilité comptable attendu des fonds propres, pondéré par le taux de réinvestissement.

**Application 3 (p. 5) et Application 6 (p. 8) — voir section 4.**

---

### 2.1.2. Estimation du coût des capitaux propres par le MEDAF (p. 6–7)

#### a. Définition (p. 6)

Le **MEDAF** (modèle d'équilibre des actifs financiers) permet d'évaluer la **rentabilité exigée d'un actif risqué**. La rentabilité exigée par l'actionnaire résulte de la somme :

- de la rentabilité offerte par un **actif sans risque** ; et
- d'une **prime de risque** égale à \( \beta \) fois la prime de risque du marché.

$$
R_a = R_f + \beta\,(R_M - R_f)
$$

En optique **prévisionnelle**, on raisonne en rentabilité espérée :

$$
E(R_a) = R_f + \beta\,\big(E(R_M) - R_f\big)
$$

| Symbole | Signification |
|---|---|
| \( E(R_a) \) | Espérance de rentabilité exigée ou obtenue par l'actionnaire |
| \( R_f \) | Rentabilité certaine de l'actif sans risque |
| \( E(R_M) \) | Espérance de rentabilité du marché |
| \( E(R_M) - R_f \) | **Prime de risque du marché** |
| \( \beta \) | Mesure la variabilité de la rentabilité de l'actif risqué par rapport à la variabilité de la rentabilité du marché |

**Interprétation.** Le marché ne rémunère que le **risque systématique** (non diversifiable), mesuré par \( \beta \). \( \beta>1 \) : titre plus risqué que le marché ; \( \beta<1 \) : moins risqué.

> **[À vérifier]** Le professeur écrit parfois \( r_m \) ou \( R_M \) (ex. Application 4 : « r_f = 5 %, r_m = 9 % »). Je lis \( r_m = R_M = \) rentabilité du marché.

#### b. La décomposition de la prime de risque (p. 7)

Le coefficient \( \beta \) traduit deux types de risque : le **risque d'exploitation** et le **risque financier**. On peut les séparer :

$$
\beta = \beta_a \left[ 1 + (1-t)\,\frac{D}{CP} \right]
$$

- \( \beta_a \) : composante du risque systématique qui ne dépend que des éléments déterminant la **rentabilité d'exploitation**, indépendante de la politique de financement. Il est dénommé **β d'exploitation (ou β économique)**, par opposition au \( \beta \) **fonds propres**.
- \( D/CP \) : ratio d'endettement mesuré à partir des **valeurs de marché** des dettes et des capitaux propres.
- \( t \) : taux d'impôt sur les sociétés.

En associant la relation fondamentale du MEDAF à cette décomposition, le taux requis comprend, outre le taux sans risque, **deux primes de risque** (exploitation et financière) dont la somme constitue la **prime de risque totale** :

$$
R_a = R_f + \beta_a\,[R_M - R_f] + \beta_a\,[R_M - R_f]\,(1-t)\,\frac{D}{CP}
$$

| Terme | Signification |
|---|---|
| \( \beta_a [R_M - R_f] \) | **Prime de risque d'exploitation** |
| \( \beta_a [R_M - R_f](1-t)\,D/CP \) | **Prime de risque financier** : d'autant plus importante que l'endettement est élevé |

**Interprétation.** Plus l'entreprise s'endette, plus le \( \beta \) des fonds propres et le coût \( k_e \) augmentent, même si les actifs ne changent pas.

**Erreur fréquente :** utiliser \( D/CP \) en valeurs **comptables** : le cours exige les valeurs de marché.

**Applications 4, 5 et 6 — voir section 4.**

---

### 2.2. Évaluation des coûts de financement par emprunt et par crédit-bail (p. 8)

Les méthodes d'évaluation du coût des emprunts reposent sur les **principes actuariels**. Le coût du crédit-bail s'analyse en tant que **mode de financement substituable à l'emprunt**.

### 2.2.1. Évaluation du coût de la dette

#### 2.2.1.1. Le taux actuariel (p. 9)

**Définition.** Le coût de la dette s'évalue par le **taux actuariel net après impôt**. C'est un coût **explicite**, car il y a sortie effective de liquidités pour l'entreprise.

**Notations :** \( R_t \) = remboursement en capital en \( t \) ; \( I_t \) = intérêts payés en \( t \) ; \( T \) = taux d'imposition ; \( M \) = montant emprunté ; \( n \) = durée de vie de l'emprunt.

Le **taux actuariel \( r \) après impôt** est le taux d'actualisation qui permet d'égaliser le montant emprunté \( M \) et la valeur actualisée des remboursements et des frais financiers **après impôt** (compte tenu de leur déductibilité) :

$$
M = \sum_{t=1}^{n} \frac{R_t + I_t\,(1-T)}{(1+r)^t}
$$

**Remarque du professeur.** Cette relation doit être **ajustée** si l'emprunt comporte des **primes d'émission et de remboursement**, qui modifient les montants reçus et remboursés. Il faut aussi tenir compte des **frais** (frais d'émission, commissions diverses…) pour obtenir le véritable coût.

**Interprétation.** \( r \) est le TRI, du point de vue de l'emprunteur, des flux nets de l'emprunt. Sans fiscalité, \( T=0 \) ; sans frais, \( r \) = taux nominal ; avec frais, \( r \) > taux nominal (on reçoit moins que \( M \)).

**Méthode de résolution (à connaître pour l'examen) :**

1. Calculer le **montant réellement reçu** : \( M - \) frais.
2. Construire le **tableau d'amortissement**.
3. Établir les **flux décaissés** chaque année (annuités, ou \( R_t + I_t(1-T) \) si fiscalité).
4. Chercher \( r \) tel que *montant reçu = somme actualisée des flux* (calculatrice : TRI, ou interpolation linéaire entre deux taux).

#### 2.2.1.2. L'amortissement d'un emprunt (p. 9–10)

L'évaluation du coût nécessite le **tableau d'amortissement** (remboursements et frais financiers). Les principes sont simples pour les deux modes les plus répandus (amortissement constant et annuités constantes).

\( A_t \) est l'annuité de la période \( t \), constituée de l'amortissement du capital emprunté et des intérêts : \( A_t = R_t + I_t \). Elle est payée **en fin de période**. \( i \) est le taux nominal, \( n \) la durée de vie.

> **Principe :** la somme actualisée **au taux nominal** des annuités est égale au montant emprunté.

**Colonnes du tableau :** Année · Capital (début de période) · Amortissement · Intérêts · Annuité · CFP (capital fin de période).

##### - L'emprunt à amortissement constant (p. 9)

L'amortissement annuel du capital est constant ⇒ \( R_t = M/n \). Par conséquent, les annuités décroissent :

$$
A_{t+1} - A_t = -\frac{M}{n}\times i
$$

##### - L'emprunt à annuités constantes (p. 10)

L'annuité constante \( A \) qui comprend les remboursements et les intérêts s'évalue à partir de :

$$
A = \frac{M \times i}{1-(1+i)^{-n}}
$$

Les annuités étant constantes, **les amortissements successifs forment une progression géométrique croissante de raison \( 1+i \)** :

$$
R_{t+1} = R_t\,(1+i)
$$

##### - Le remboursement in fine (p. 11)

Le capital est remboursé **en une seule fois à l'échéance** ; les intérêts \( M\times i \) sont payés chaque année. *(Le professeur ne donne pas de formule : seul le tableau vierge de l'Application 9 figure sur la photo.)*

**Applications 7, 8, 9, 10 — voir section 4.**

---

#### 2.2.2. Évaluation du coût de financement par crédit-bail (p. 13)

**Définition.** Le contrat de **crédit-bail** est un contrat de **location portant sur un bien meuble ou immeuble, assorti d'une option d'achat à un prix fixé d'avance**.

Le crédit-bail est un mode de financement particulier, qui s'analyse comme un **substitut à l'emprunt** et dont le coût peut être évalué sous forme d'un **taux actuariel**.

**Logique.** Le coût pour le locataire est la **contrepartie de la rentabilité pour le bailleur** ; il suffit d'identifier les flux qui déterminent la rentabilité de l'opération pour ce dernier.

**Formule (p. 13) :**

$$
I = \sum_{t=1}^{n} \frac{(1-T)\,L_t + T\,D_t}{(1+r)^t} + \frac{VR}{(1+r)^n}
$$

| Symbole | Signification |
|---|---|
| \( L \) (ou \( L_t \)) | Le loyer |
| \( D_t \) | Dotation d'amortissement |
| \( VR \) | Prix de revente (**option de rachat**) |
| \( I \) | Montant de l'investissement |
| \( T \) | Taux d'impôt |
| \( r \) | Taux actuariel recherché (coût de financement / rentabilité du bailleur) |

> **[À vérifier]** Sur la photo le taux d'actualisation est écrit « \( r \) » dans les dénominateurs, même si le professeur ne l'a pas défini dans la légende. Je le lis comme le coût du crédit-bail.

**Analyse des composantes du coût.** En dehors de la valeur de l'option de rachat (qui s'analyse comme un **loyer résiduel**), le coût comprend deux composantes :

- une composante **explicite** \( (1-T)\,L_t \) : le loyer après impôt ;
- une composante **implicite** \( T\cdot D_t \) : le **coût d'opportunité** dû à la perte des économies d'impôt liées à la déductibilité fiscale des dotations aux amortissements, auxquelles l'entreprise locataire renonce en n'étant plus propriétaire.

**Application 11 — voir section 4.**

---

### 3. Le coût moyen pondéré du capital — CMPC (p. 14)

**Introduction [Cours].** Jusque-là, on a considéré séparément les sources de financement (essentiellement fonds propres et dettes) et évalué leur coût séparément. En réalité, les entreprises n'ont pratiquement jamais recours à l'une ou l'autre exclusivement : le coût du capital est un **mélange** du coût des fonds propres et de celui des dettes.

**Définition.** Ce coût global \( k \) s'appelle le **coût moyen pondéré du capital**. On l'obtient en pondérant le coût des différentes sources par leur contribution respective dans la structure de financement. Le **poids** de chaque source résulte de leurs **valeurs de marché** respectives et **non des valeurs comptables**.

**Formule :**

$$
CMPC = K_e \cdot \frac{CP}{CP + D} + K_d\,(1-T)\cdot \frac{D}{CP + D}
$$

| Symbole | Signification |
|---|---|
| \( K_e \) | Coût des fonds propres |
| \( K_d \) | Coût de la dette (avant impôt) |
| \( CP \) | Montant total des fonds propres (valeur de marché) |
| \( D \) | Montant total des dettes (valeur de marché) |
| \( T \) | Taux d'impôt |

**Utilité.** Le CMPC sert notamment de **taux d'actualisation** dans la méthode d'actualisation des flux de trésorerie disponibles (**DCF**).

**Rappel [Cours].** La valeur de marché de l'entreprise résulte de la valeur actualisée des flux de liquidités générés par son actif économique : \( VE = V_{CP} + V_D \). Déduire de cette valeur celle de marché des dettes donne la valeur des fonds propres (titres détenus par les actionnaires).

**Erreurs à éviter :**

- Oublier \( (1-T) \) sur la dette (économie d'impôt sur les intérêts).
- Pondérer avec les valeurs comptables.
- Utiliser le coupon de l'ancienne dette comme \( K_d \) alors que le coût *actuel* d'endettement est connu (voir Application 13).

**Applications 12 et 13 — voir section 4.**

---

## 3. Formules et méthodes de calcul

Notations du professeur conservées. Tous les calculs de la section 4 ont été recalculés (Python) en plus du calcul manuel.

### 3.1. Coût des fonds propres

| # | Objectif | Formule | Hypothèses | Procédure | Erreurs fréquentes |
|---|---|---|---|---|---|
| F1 | Coût des FP, dividendes constants (Fisher) | \( k = D/P_0 \) | Dividende constant, infini | Diviser le dividende par le cours | Utiliser si \( g\neq0 \) |
| F2 | Coût des FP, dividendes croissants (Gordon-Shapiro) | \( k = \dfrac{D_1}{P_0} + g \), \( D_1 = D_0(1+g) \) | \( g \) constant, \( k>g \), horizon infini | 1) \( D_1 \) 2) \( D_1/P_0 \) 3) \( +g \) | Confondre \( D_0 \) et \( D_1 \) |
| F3 | Taux de croissance si « doublement en \( n \) ans » | \( (1+g)^n = 2 \Rightarrow g = 2^{1/n}-1 \) | Croissance régulière | Racine \( n \)-ième | Diviser 100 % par \( n \) |
| F4 | Coût des FP via PER, croissance nulle | \( r = B/P_0 = 1/\text{PER} \) | Bénéfice constant | Bénéfice / cours | Appliquer en croissance |
| F5 | Coût des FP via PER, croissance (Charreaux) | \( r = \dfrac{B(1-b)}{P_0} + bK \) | \( b \) et \( K \) constants | 1) \( B(1-b) \) 2) \( /P_0 \) 3) \( +bK \) | Confondre \( b \) (réinvest.) et \( d \) (distrib.) |
| F6 | Croissance des dividendes | \( g = b\times K \) | \( b \) constant | Produit | – |
| F7 | MEDAF | \( R_a = R_f + \beta(R_M-R_f) \) | Marché efficient, \( \beta \) stable | 1) Prime de marché 2) \( \times\beta \) 3) \( +R_f \) | Oublier de soustraire \( R_f \) |
| F8 | Bêta économique | \( \beta_a = \dfrac{\beta}{1+(1-t)\,D/CP} \) | \( D/CP \) en valeurs de marché | Calcul direct | \( D/CP \) comptable |
| F9 | Décomposition prime | Prime exploitation \( =\beta_a(R_M-R_f) \) ; prime financière \( =\beta_a(R_M-R_f)(1-t)D/CP \) | idem | Calculer la 1re puis par différence | Oublier que somme = prime totale \( \beta(R_M-R_f) \) |

### 3.2. Coût de la dette et du crédit-bail

| # | Objectif | Formule | Procédure |
|---|---|---|---|
| F10 | Taux actuariel après impôt | \( M=\sum_t \dfrac{R_t+I_t(1-T)}{(1+r)^t} \) | Montant reçu \( =M-\) frais ; chercher \( r \) (TRI) |
| F11 | Annuité constante | \( A=\dfrac{M\,i}{1-(1+i)^{-n}} \) | Calculer \( A \), puis \( I_t=i\times \text{capital début} \), \( R_t=A-I_t \) |
| F12 | Amortissements en annuités constantes | \( R_{t+1}=R_t(1+i) \) | Contrôle : \( R_1=A-Mi \) |
| F13 | Amortissement constant | \( R_t=M/n \) ; \( A_{t+1}-A_t=-(M/n)\,i \) | Annuités décroissantes |
| F14 | In fine | \( I_t=Mi \) chaque année ; \( R_n=M \) | – |
| F15 | Crédit-bail | \( I=\sum_t\frac{(1-T)L_t+TD_t}{(1+r)^t}+\frac{VR}{(1+r)^n} \) | Flux annuel \( (1-T)L+TD \), puis \( VR \) à \( n \) ; chercher \( r \) |

### 3.3. CMPC

| # | Formule | Procédure |
|---|---|---|
| F16 | \( CMPC=K_e\frac{CP}{CP+D}+K_d(1-T)\frac{D}{CP+D} \) | 1) \( CP \) et \( D \) en valeur de marché 2) poids 3) \( K_e \) (MEDAF/Gordon) 4) \( K_d \) actuel × \( (1-T) \) 5) somme |
| F17 | \( VE=V_{CP}+V_D \) | \( V_{CP}=\) nombre d'actions \( \times \) cours |

**Recherche de \( r \) sans calculatrice financière :** calculer la valeur actuelle des flux à deux taux \( r_1<r<r_2 \) encadrant \( M \), puis interpoler : \( r\approx r_1+(r_2-r_1)\dfrac{VA(r_1)-M}{VA(r_1)-VA(r_2)} \).

---

## 4. Applications du cours

> **Important.** Le professeur ne fournit pas les corrections (sauf le tableau de l'Application 7, écrit à la main). Les corrections ci-dessous sont **calculées par moi** à partir des données de l'énoncé. Les hypothèses que j'ai dû poser sont signalées **[À vérifier]**. Les Applications 1 et 2 sont photographiées p. 4, l'Application 3 p. 5, etc.

### Application 1 — INER-GI (p. 4)

**Énoncé.** Actions cotées à **500 €**. Coût des capitaux propres si les dividendes attendus sont : (1) constants et égaux à 40 € ; (2) croissants au taux annuel de 4 % avec \( D_1 = 30 \) € ?

**Méthode.** (1) Fisher (dividende perpétuel) ; (2) Gordon-Shapiro.

1. \( k = D/P_0 = 40/500 = 0{,}08 = \mathbf{8\,\%} \)
2. \( k = D_1/P_0 + g = 30/500 + 0{,}04 = 0{,}06+0{,}04 = \mathbf{10\,\%} \)

**Interprétation.** Dans le cas (2), le rendement courant est plus faible (6 %) mais compensé par la croissance (4 %), d'où un coût plus élevé : les actionnaires exigent 10 %.
**Piège :** ici \( D_1 \) est donné directement, ne pas le multiplier par \( 1+g \).

### Application 2 — BRANT (p. 4)

**Énoncé (2008-2012).** Dettes à coût constant de 12 % ; société exonérée d'impôt ; dividendes payés au moment de la constatation des bénéfices ; taux de rétention 80 % ; prix de l'action 1 000 début 2008 et 1 045 fin 2012.

| | 2008 | 2009 | 2010 | 2011 | 2012 |
|---|---|---|---|---|---|
| CA | 2 200 | 2 400 | 2 600 | 3 000 | 3 500 |
| Charges d'exploitation | 820 | 940 | 1 000 | 1 150 | 1 200 |
| Dotations aux amortissements | 500 | 500 | 600 | 600 | 600 |
| Dettes | 450 | 550 | 600 | 730 | 900 |

**Q1. Coût des capitaux propres.**

*Méthode.* Le coût des FP est le taux qui égalise le prix d'achat (1 000) et la valeur actuelle des dividendes + du prix de revente (modèle de Fisher avec cession).

*Étape 1 — Bénéfice net* = CA − charges − dotations − intérêts (12 % × dettes) ; pas d'IS.

| | 2008 | 2009 | 2010 | 2011 | 2012 |
|---|---|---|---|---|---|
| Résultat d'exploitation | 880 | 960 | 1 000 | 1 250 | 1 700 |
| Intérêts (12 %) | 54 | 66 | 72 | 87,6 | 108 |
| **Bénéfice net** | 826 | 894 | 928 | 1 162,4 | 1 592 |
| **Dividende** (20 %) | 165,2 | 178,8 | 185,6 | 232,48 | 318,4 |

*Étape 2 — Équation :*

$$
1000=\frac{165{,}2}{1+k}+\frac{178{,}8}{(1+k)^2}+\frac{185{,}6}{(1+k)^3}+\frac{232{,}48}{(1+k)^4}+\frac{318{,}4+1045}{(1+k)^5}
$$

*Étape 3 — Résolution* (TRI / interpolation) : **\( k \approx 20{,}9\,\% \)**.

**Q2. Vente en 2010 au prix de 900 :**

$$
1000=\frac{165{,}2}{1+k}+\frac{178{,}8}{(1+k)^2}+\frac{185{,}6+900}{(1+k)^3}\;\Rightarrow\; k\approx \mathbf{14{,}7\,\%}
$$

**Interprétation.** Le coût (rendement réalisé) dépend de l'horizon : revendre à 900 (moins que le prix d'achat) fait chuter le taux.
**[À vérifier]** Le tableau ne précise pas si l'intérêt se calcule sur la dette de fin d'année (retenu ici) ou de début d'année. Un autre choix de convention modifierait légèrement le résultat. De plus, les dividendes sont considérés comme versés à la fin de chaque année.

### Application 3 — ALTEC (p. 5)

**Énoncé.** Résultats et dividende devraient **doubler en 5 ans**. Rentabilité exigée 20 %. Dernier dividende versé : 5 €. Estimer le prix de l'action.

1. Taux de croissance : \( (1+g)^5 = 2 \Rightarrow g = 2^{1/5}-1 = 14{,}87\,\% \)
2. \( D_1 = D_0(1+g) = 5\times1{,}1487 = 5{,}743 \) €
3. \( P_0 = \dfrac{D_1}{k-g} = \dfrac{5{,}743}{0{,}20-0{,}1487} = \mathbf{\approx 111{,}96\ \text{€}} \)

**Interprétation.** L'action vaut environ 112 € par action. **Piège :** \( g \neq 100\%/5 = 20\% \) (taux linéaire) ; avec 20 %, \( k-g=0 \) : impossible.

### Application 4 — BDM (p. 7)

**Données.** \( r_f=5\,\% \), \( r_m=9\,\% \), \( \beta=1{,}55 \), \( D/CP=0{,}75 \), \( IS=33\,\% \).

1. **Prime de risque du marché** : \( r_m-r_f = 9-5 = \mathbf{4\,\%} \).
2. **Prime de risque** (du titre) : \( \beta(r_m-r_f)=1{,}55\times4=\mathbf{6{,}2\,\%} \).
3. **Coût des capitaux propres** : \( 5+6{,}2=\mathbf{11{,}2\,\%} \).
4. **Décomposition** :
   - \( \beta_a=\dfrac{1{,}55}{1+0{,}67\times0{,}75}=\dfrac{1{,}55}{1{,}5025}=1{,}0316 \)
   - Prime d'exploitation \( =1{,}0316\times4=\mathbf{4{,}13\,\%} \)
   - Prime financière \( =1{,}0316\times4\times0{,}67\times0{,}75=\mathbf{2{,}07\,\%} \)
   - Contrôle : \( 4{,}13+2{,}07=6{,}2\,\% \) ✔

**Interprétation.** Un tiers environ de la prime totale (2,07/6,2) vient de l'endettement.

### Application 5 — LIMAG (p. 8)

**Données.** \( \beta=1{,}5 \) ; \( D/CP=1 \) ; \( t=30\,\% \) ; \( R_f=10\,\% \) ; \( R_M=14\,\% \).

1. \( K_e=10+1{,}5\times(14-10)=\mathbf{16\,\%} \).
2. \( \beta_a=\dfrac{1{,}5}{1+0{,}7\times1}=0{,}882 \)
   - Prime d'exploitation \( =0{,}882\times4=\mathbf{3{,}53\,\%} \)
   - Prime financière \( =0{,}882\times4\times0{,}7\times1=\mathbf{2{,}47\,\%} \)
   - Total \( =6\,\% \) ✔ (= \( 16-10 \)).

### Application 6 (Synthèse) — MATEX (p. 8)

**Q1.** \( P_0=700 \) Dh.
- Cas 1 (dividende constant 50) : \( k=50/700=\mathbf{7{,}14\,\%} \)
- Cas 2 (\( D_0=40 \), \( g=5\,\% \)) : \( D_1=42 \) ; \( k=42/700+5\,\%=6\,\%+5\,\%=\mathbf{11\,\%} \)

**Q2.** Bénéfice par action stable de 80 : \( r=B/P_0=80/700=\mathbf{11{,}43\,\%} \) (inverse du PER ; PER = 8,75).

**Q3.** \( K=10\,\% \) ; \( b=40\,\% \). **[À vérifier]** On garde \( B=80 \) (l'énoncé ne le répète pas).

$$
r=\frac{B(1-b)}{P_0}+bK=\frac{80\times0{,}6}{700}+0{,}4\times0{,}10=6{,}86\,\%+4\,\%=\mathbf{10{,}86\,\%}
$$

**Q4.** \( R_f=4\,\% \), \( R_M=9\,\% \), \( \beta=1{,}35 \) : prime de marché \( =5\,\% \) ; \( K_e=4+1{,}35\times5=\mathbf{10{,}75\,\%} \).

**Synthèse.** Les quatre approches donnent des résultats compris entre 7 % et 11,4 % : chaque modèle repose sur ses hypothèses (dividende constant, croissance, bénéfice stable, risque systématique).

### Application 7 — Emprunt à amortissement constant (p. 10)

**Énoncé.** \( M=100\,000 \), 5 ans, \( i=8\,\% \), frais de dossier 5 000. Q1 tableau ; Q2 coût sans fiscalité ; Q3 coût en présence de frais de commissions de 2 500.

**Q1. Tableau (amortissement constant : \( 100\,000/5=20\,000 \))**

| Année | Capital | Amortissement | Intérêts | Annuité | CFP |
|---|---|---|---|---|---|
| 1 | 100 000 | 20 000 | 8 000 | 28 000 | 80 000 |
| 2 | 80 000 | 20 000 | 6 400 | 26 400 | 60 000 |
| 3 | 60 000 | 20 000 | 4 800 | 24 800 | 40 000 |
| 4 | 40 000 | 20 000 | **3 200** | 23 200 | 20 000 |
| 5 | 20 000 | 20 000 | 1 600 | 21 600 | 0 |
| **Total** | | **100 000** | **24 000** | **124 000** | |

> **[À vérifier]** Dans le tableau manuscrit du professeur : (a) l'intérêt de l'année 4 est écrit « 3 800 » alors que \( 40\,000\times8\,\%=3\,200 \) (l'annuité 23 200 confirme 3 200) ; (b) le total des amortissements est écrit « 20 000 » alors qu'il vaut 100 000. Je corrige les deux.

**Q2. Coût sans fiscalité.** On reçoit \( 100\,000-5\,000=95\,000 \). On cherche \( r \) :

$$
95\,000=\frac{28\,000}{1+r}+\frac{26\,400}{(1+r)^2}+\frac{24\,800}{(1+r)^3}+\frac{23\,200}{(1+r)^4}+\frac{21\,600}{(1+r)^5}
$$

- À 10 % : VA = 95 163 (> 95 000).
- À 11 % : VA = 92 887 (< 95 000).
- Interpolation : \( r\approx10\%+\dfrac{95\,163-95\,000}{95\,163-92\,887}\approx \mathbf{10{,}07\,\%} \).

**Q3. Avec commissions de 2 500.** **[À vérifier]** Je les considère en **supplément** des 5 000 de frais de dossier. Montant reçu \( =100\,000-5\,000-2\,500=92\,500 \) ⇒ \( r\approx\mathbf{11{,}17\,\%} \).

**Interprétation.** Le coût effectif dépasse toujours le taux nominal (8 %) : les frais réduisent le montant réellement reçu.

### Application 8 — Annuités constantes (p. 11)

**Énoncé.** \( M=100\,000 \), 5 ans, 8 %, frais de dossier 2 500. Tableau + coût sans fiscalité.

$$
A=\frac{100\,000\times0{,}08}{1-1{,}08^{-5}}=25\,045{,}65
$$

| Année | Capital | Amortissement | Intérêts | Annuité | CFP |
|---|---|---|---|---|---|
| 1 | 100 000 | 17 045,65 | 8 000,00 | 25 045,65 | 82 954,35 |
| 2 | 82 954,35 | 18 409,30 | 6 636,35 | 25 045,65 | 64 545,06 |
| 3 | 64 545,06 | 19 882,04 | 5 163,60 | 25 045,65 | 44 663,02 |
| 4 | 44 663,02 | 21 472,60 | 3 573,04 | 25 045,65 | 23 190,41 |
| 5 | 23 190,41 | 23 190,41 | 1 855,23 | 25 045,65 | 0 |
| **Total** | | **100 000** | **≈ 25 228** | **≈ 125 228** | |

*Contrôle :* \( 17\,045{,}65\times1{,}08=18\,409{,}30 \) ✔ (progression géométrique de raison 1,08).

**Coût.** \( 97\,500=25\,045{,}65\times\dfrac{1-(1+r)^{-5}}{r}\Rightarrow r\approx\mathbf{8{,}97\,\%} \).

### Application 9 — Remboursement in fine (p. 11)

Même emprunt, frais 2 500.

| Année | Capital | Amortissement | Intérêts | Annuité | CFP |
|---|---|---|---|---|---|
| 1 | 100 000 | 0 | 8 000 | 8 000 | 100 000 |
| 2 | 100 000 | 0 | 8 000 | 8 000 | 100 000 |
| 3 | 100 000 | 0 | 8 000 | 8 000 | 100 000 |
| 4 | 100 000 | 0 | 8 000 | 8 000 | 100 000 |
| 5 | 100 000 | 100 000 | 8 000 | 108 000 | 0 |
| **Total** | | **100 000** | **40 000** | **140 000** | |

**Coût.** \( 97\,500=\sum\dfrac{8\,000}{(1+r)^t}+\dfrac{100\,000}{(1+r)^5}\Rightarrow r\approx\mathbf{8{,}64\,\%} \).

**Comparaison 8/9 :** le coût est plus faible en in fine (8,64 %) qu'en annuités constantes (8,97 %), car les frais (2 500) s'étalent sur un capital qui reste plus longtemps entièrement disponible.

### Application 10 — Emprunt 10 000, 10 %, avec fiscalité (p. 12)

**Q1. Tableau (annuités constantes).** \( A=\dfrac{10\,000\times0{,}10}{1-1{,}1^{-5}}=2\,637{,}97 \)

| Année | Capital | Amortissement | Intérêts | Annuité | CFP |
|---|---|---|---|---|---|
| 1 | 10 000 | 1 637,97 | 1 000,00 | 2 637,97 | 8 362,03 |
| 2 | 8 362,03 | 1 801,77 | 836,20 | 2 637,97 | 6 560,25 |
| 3 | 6 560,25 | 1 981,95 | 656,03 | 2 637,97 | 4 578,30 |
| 4 | 4 578,30 | 2 180,14 | 457,83 | 2 637,97 | 2 398,16 |
| 5 | 2 398,16 | 2 398,16 | 239,82 | 2 637,97 | 0 |

**Q2. Coût avec fiscalité (IS = 30 %).** Frais d'émission 200 + commission 300 = **500** ⇒ montant reçu \( =9\,500 \).

Flux décaissés = amortissement + intérêt après impôt :

| Année | Intérêt après impôt \( I(1-0{,}3) \) | Flux \( R_t+I_t(1-T) \) |
|---|---|---|
| 1 | 700,00 | 2 337,97 |
| 2 | 585,34 | 2 387,11 |
| 3 | 459,22 | 2 441,17 |
| 4 | 320,48 | 2 500,63 |
| 5 | 167,87 | 2 566,03 |

$$
9\,500=\sum_{t=1}^{5}\frac{R_t+I_t(1-0{,}3)}{(1+r)^t}\;\Rightarrow\; r\approx\mathbf{8{,}91\,\%}
$$

*Contrôle :* sans frais, le coût après impôt est exactement \( 10\,\%\times0{,}7=7\,\% \). Les frais le portent à 8,91 %.

> **[À vérifier]** (a) La dernière colonne du tableau 2 du professeur est intitulée « Annuité (A+I) » ; je l'interprète comme le flux « amortissement + intérêt après impôt ». (b) Je suppose que les frais (500) ne sont **pas** déductibles. Si ton professeur les déduit (étalés sur 5 ans, économie d'impôt de 30 par an), le flux annuel diminue de 30 et le coût devient ≈ 8,45 %. Utilise la convention du professeur.

### Application 11 — Crédit-bail (p. 13)

**Énoncé.** Bien de **1 000**, durée de vie 5 ans, loyer annuel 300, valeur de revente 20 en fin d'année 5, IS 30 %. Évaluer le coût de financement (rentabilité pour le bailleur).

1. Dotation annuelle (amortissement linéaire sur 5 ans) : \( D_t=1\,000/5=200 \). **[À vérifier]** : l'énoncé parle de « durée de vie de cinq ans » ; je suppose un amortissement linéaire sans valeur résiduelle.
2. Flux annuel : \( (1-T)L+TD=0{,}7\times300+0{,}3\times200=210+60=270 \)
3. Équation : \( 1\,000=\sum_{t=1}^{5}\dfrac{270}{(1+r)^t}+\dfrac{20}{(1+r)^5} \)
4. Vérification : à 10 % : \( 270\times3{,}7908+20\times0{,}6209=1\,023{,}5+12{,}4=1\,035{,}9 \) (> 1 000) ; à 12 % : \( 270\times3{,}6048+20\times0{,}5674=973{,}3+11{,}3=984{,}6 \) (< 1 000).
5. Interpolation ⇒ **\( r\approx11{,}4\,\% \)**.

**Interprétation.** Le crédit-bail coûte environ 11,4 % après impôt (comparer au coût d'un emprunt équivalent pour choisir le mode de financement).

### Application 12 — PANEL (p. 15)

**Données.** 100 M d'actions, cours 20, \( \beta=0{,}7 \) ; dette de marché 500 M ; \( R_f=4\,\% \) ; prime de risque de marché 5 %.

1. **Valeur de l'entreprise** : \( V_{CP}=100\times20=2\,000 \) M ; \( VE=2\,000+500=\mathbf{2\,500\ \text{M}} \).
2. **Coût des actions** : \( K_e=4+0{,}7\times5=\mathbf{7{,}5\,\%} \).
3. **CMPC** : poids \( CP/(CP+D)=80\,\% \), \( D/(CP+D)=20\,\% \).

$$
CMPC=0{,}8\times7{,}5\,\%+0{,}2\times K_d(1-T)=6\,\%+0{,}2\,K_d(1-T)
$$

> **[À vérifier] — donnée manquante.** L'énoncé photographié ne donne **ni le coût de la dette \( K_d \), ni le taux d'impôt \( T \)**. Je ne peux donc pas donner le CMPC final avec certitude. *À titre purement illustratif (hypothèse de ma part)* : avec \( K_d=5\,\% \) et \( T=30\,\% \), CMPC \( =6+0{,}7=6{,}7\,\% \). **Vérifie dans ton polycopié ou auprès du professeur si ces données figurent ailleurs (suite de l'énoncé ?).**

### Application 13 — PEREG (p. 15)

**Données.** 1 M d'actions à 20 € ; \( \beta=1{,}2 \) ; prime de marché 3,5 % ; \( R_f=4\,\% \). Dette obligataire à 4,5 %, nominal 40 €, remboursable au pair, 4 M€ au bilan ; cote actuelle 38 € ; la société peut aujourd'hui s'endetter à 4,8 % ; IS 33 %.

1. \( K_e=4+1{,}2\times3{,}5=\mathbf{8{,}2\,\%} \).
2. Valeur de marché des FP : \( 1\,000\,000\times20=20\ \text{M€} \).
3. Nombre d'obligations : \( 4\,000\,000/40=100\,000 \). **Valeur de marché de la dette** \( =100\,000\times38=3{,}8 \) M€ (et non 4 M€ comptable).
4. Coût de la dette : on retient le **coût actuel d'endettement 4,8 %** (et non le coupon de 4,5 %, coût historique) ; après impôt : \( 4{,}8\times(1-0{,}33)=3{,}216\,\% \).
5. Poids : \( CP/(CP+D)=20/23{,}8=84{,}03\,\% \) ; \( D/(CP+D)=15{,}97\,\% \).

$$
CMPC=0{,}8403\times8{,}2\,\%+0{,}1597\times3{,}216\,\%=6{,}891\,\%+0{,}514\,\%\approx\mathbf{7{,}40\,\%}
$$

**Interprétation.** Le CMPC (≈ 7,4 %) est le taux minimal de rentabilité exigé des projets de PEREG (même risque). **Pièges :** poids en valeur de marché (3,8 et non 4) ; coût de la dette *actuel* après IS.

---

## 5. Exercices corrigés du PDF

Le PDF (Boughaba, 304 p.) ne contient **pas** d'exercices reprenant les données des Applications 1 à 13 du professeur. Il contient en revanche deux éléments directement liés au chapitre : un exemple de **coût du capital marginal** (p. 143-144 du livre) et un exercice de lecture du **MEDAF** (exercice 14, p. 171-173). Je les reprends ci-dessous.

### Exercice A — Coût moyen pondéré et coût du capital marginal (livre, p. 143-144)

**A. Énoncé.** Situation initiale (en KDA) : fonds social 10 000 (coût 10 %), réserves 30 000 (20 %), dettes MLT 20 000 (15 %), dettes CT 40 000 (20 %). L'entreprise réalise un investissement de **50 000** sur **emprunt MLT** à 10 %, soit **5 %** après IBS (IBS = 50 %). On suppose que le coût des fonds propres passe de 10 % à 7 %.

**B. Analyse.** L'exercice évalue la maîtrise du CMPC et de la notion de **coût marginal** : variation du coût total du capital rapportée à la variation du capital.

**C. Données.**

| Source | Capitaux | Coût avant | Coût après |
|---|---|---|---|
| Fonds social | 10 000 | 10 % | 7 % |
| Réserves | 30 000 | 20 % | 20 % |
| Dettes MLT | 20 000 | 15 % | 15 % |
| Dettes CT | 40 000 | 20 % | 20 % |
| Supplément dettes MLT | 50 000 | – | 5 % (après IS) |

**D. Méthode.** CMPC = \( \sum \) poids × coût ; coût marginal \( =\dfrac{\Delta(\text{coût total en montant})}{\Delta\text{capital}} \).

**E. Correction.**

1. *Avant :* poids 1/10, 3/10, 2/10, 4/10 ⇒ \( 1\%+6\%+3\%+8\%=\mathbf{18\,\%} \) ⇒ coût en montant \( =18\,000 \).
2. *Après :* capital total 150 000 ⇒ \( 0{,}467\%+4\%+2\%+5{,}333\%+1{,}667\%=13{,}47\,\% \) ⇒ \( 150\,000\times13{,}467\%=20\,200 \).
3. *Écart :* \( 20\,200-18\,000=+2\,200 \) pour \( +50\,000 \) de capital :

$$
\text{coût marginal}=\frac{2\,200}{50\,000}=\mathbf{4{,}4\,\%}
$$

**F. Vérification.** J'ai recalculé : tous les montants du livre sont exacts (le livre écrit 13,46 % par troncature ; l'arrondi est 13,47 %).
**G. À retenir.** Le coût marginal peut être très inférieur au CMPC quand l'opération s'accompagne d'une baisse du coût des fonds propres (hypothèse forte, difficile à estimer en pratique, comme le souligne l'auteur).

### Exercice B — Lecture graphique du MEDAF (livre, ex. 14, p. 171-173)

**A. Énoncé.** Six actifs/projets sont placés dans le plan \( E(R) \) / \( \beta \) par rapport à la **droite des actifs financiers** (Bourse de New York) : (1) US Steel, (2) Exxon, (3) Morgan Trust, (4) projet AEP d'Albany, (5) projet gaz de l'Oregon, (6) projet Toyota à San Diego. Commenter.

**E. Correction du livre (lecture) :**

- L'ordonnée à l'origine (9 % dans le livre) est le taux de placement **sans risque** (\( \beta=0 \)).
- \( \beta_i=\dfrac{COV(R_i;R_m)}{VAR(R_m)} \) mesure le risque systématique : plus \( \beta \) est grand, plus la prime de risque est élevée.
- La droite exprime le **rendement minimum acceptable** (coût du capital) = *taux de rejet*.
- Les projets **2, 6 et 3**, situés au-dessus de la droite, sont **acceptés** : leur \( E(R) \) dépasse celle exigée par le marché pour leur risque.
- Les projets **5, 4 et 1**, situés au-dessous, sont **rejetés**.

**G. À retenir.** Règle de décision : accepter si \( E(R_{projet}) > R_f+\beta(R_M-R_f) \).

> **[À vérifier]** La figure du PDF est mal extraite en texte ; je me fie à la correction écrite. Le « 9 % » du livre est donné comme taux sans risque sans plus de précision.

---

## 6. Compléments théoriques du PDF (non directement abordés dans le chapitre)

### 6.1. La thèse de Modigliani-Miller et la structure optimale du capital (livre, p. 141-143)

- **Thèse M&M :** sur un marché financier parfait (information parfaite, atomicité) et sans fiscalité, **il n'existe pas de structure optimale** : les différentes formes de financement sont équivalentes et le coût du capital est constant. Le livre la juge dépassée, d'intérêt surtout historique, mais utile car elle relie **structure du capital, coût du capital et valeur de l'entreprise**.
- **Théorie traditionnelle :** il existe une **structure optimale**, où le coût réel marginal de chaque forme de financement est le même. L'endettement reste avantageux tant que son coût est inférieur à celui des capitaux propres, mais l'effet de levier s'érode avec le risque financier croissant.
- **Relation avec le chapitre :** le professeur renvoie à M&M dans l'introduction (p. 1) et cite le « choix de la structure du capital optimale » comme usage du CMPC.

### 6.2. Le coût du capital comme indicateur (livre, p. 140)

Le livre précise que le coût du capital est « plutôt un indicateur qu'un taux » dont la mesure objective est impossible ; le taux d'opportunité exprime la stratégie et la situation de l'entreprise face au marché.

### 6.3. Fondements du MEDAF (livre, p. 150-152)

- Hypothèses : investisseurs ayant la même information et la même aversion pour le risque ⇒ même **frontière efficiente**.
- Droite des portefeuilles combinant actif sans risque et portefeuille de marché M (capital market line) : \( E(R_p)=R_F+\dfrac{E(R_m)-R_F}{\sigma_m}\sigma_p \).
- Seul le **risque systématique** est rémunéré (le risque diversifiable peut être éliminé) ⇒ \( E(R_i)=R_F+\beta_i[E(R_m)-R_F] \), **droite des actifs financiers**.
- **Application à l'investissement :** n'accepter que les projets situés au-dessus de cette droite ; le MEDAF évite l'inconvénient du taux moyen pondéré unique (chaque projet a son propre taux de rejet selon son risque).
- **Divergence de notation :** le livre écrit \( R_F \) pour le taux sans risque ; le professeur écrit \( R_f \). Je conserve la notation du professeur dans le cours. *(Dans l'extraction du livre, une formule porte « \( E(R_m)-R_p \) » : c'est une erreur d'extraction ; la formule correcte est \( E(R_m)-R_F \).)*

### 6.4. Divergence sur la formule du CMPC

- **Professeur (priorité) :** \( CMPC=K_e\frac{CP}{CP+D}+K_d(1-T)\frac{D}{CP+D} \).
- **Livre (p. 140) :** \( k_0=k_e\frac{P}{P+E}+k_i\frac{E}{P+E} \), sans \( (1-T) \) dans la formule ; dans son exemple chiffré (p. 143) le coût de la dette est pourtant pris **après impôt** (5 % = 10 % × (1 − 50 %)).
- **Conclusion :** les deux sont cohérentes si \( k_i \) du livre est entendu *après impôt*. On suit le professeur.

---

## 7. Synthèse structurée du chapitre

**Définitions incontournables**

- **Coût du capital** = rentabilité minimale exigée des investissements pour satisfaire actionnaires et créanciers ; ≠ coût des fonds propres.
- **Coût des FP** = rendement exigé par les actionnaires (non contractuel, non déductible, aléatoire).
- **Taux actuariel** = taux qui égalise le montant reçu et la valeur actualisée des décaissements (après impôt).
- **CMPC** = moyenne pondérée (valeurs de marché) du coût des FP et du coût de la dette après impôt.

**Quel modèle pour quel cas ?**

| Situation | Modèle |
|---|---|
| Dividende constant | \( k=D/P_0 \) |
| Dividende en croissance constante | \( k=D_1/P_0+g \) |
| Bénéfice constant (pas de croissance) | \( r=B/P_0 \) |
| Bénéfice avec réinvestissement \( b \) | \( r=\frac{B(1-b)}{P_0}+bK \) |
| Données de marché (\( \beta \), \( R_M \), \( R_f \)) | MEDAF |
| Dette avec frais/impôt | taux actuariel |
| Location avec option d'achat | taux actuariel du crédit-bail |

**Différences entre notions proches**

- Gordon-Shapiro (dividendes) vs inverse du PER (bénéfices) : le premier tient compte de la croissance, le second n'est valable que sans croissance (ou dans les cas \( b=0 \) / \( r=K \)).
- \( \beta \) fonds propres vs \( \beta_a \) économique : le premier inclut le risque financier ; le second seulement le risque d'exploitation.
- Amortissement constant (annuités décroissantes) vs annuités constantes (amortissements croissants de raison \( 1+i \)) vs in fine (capital à l'échéance).
- Composante explicite \( (1-T)L \) vs implicite \( T\cdot D \) du crédit-bail.

**Démarche type en examen (CMPC)** : \( K_e \) → \( K_d(1-T) \) → poids de marché → somme.

---

## 8. Tableau récapitulatif des formules

| Notion | Formule | Variables principales | Utilité | Conditions ou remarques |
|---|---|---|---|---|
| Fisher (avec cession) | \( P_0=\sum D_i(1+k)^{-i}+P_n(1+k)^{-n} \) | \( D_i \), \( P_n \), \( k \) | Coût FP sur horizon fini | \( k \) = TRI de l'actionnaire |
| Dividende constant | \( P_0=D/k \) | \( D \) | Coût FP | Perpétuité |
| Gordon-Shapiro | \( P_0=\frac{D_1}{k-g} \) ; \( k=\frac{D_1}{P_0}+g \) | \( D_1=D_0(1+g) \) | Coût FP | \( k>g \), \( D>0 \) |
| Bénéfices | \( r=B/P_0=1/\text{PER} \) | \( B \) | Coût FP | Croissance nulle |
| Charreaux | \( r=\frac{B(1-b)}{P_0}+bK \) | \( b \), \( K \) | Coût FP | \( b \) constant |
| Croissance | \( g=b\cdot K \) | \( b \), \( K \) | Lien Gordon / bénéfices | – |
| MEDAF | \( R_a=R_f+\beta(R_M-R_f) \) | \( \beta \) | Coût FP | Risque systématique |
| Bêta économique | \( \beta=\beta_a[1+(1-t)D/CP] \) | \( \beta_a \), \( D/CP \) | Séparer les risques | Valeurs de marché |
| Prime totale | \( \beta_a(R_M-R_f)\big[1+(1-t)\frac{D}{CP}\big] \) | – | Décomposition | – |
| Taux actuariel | \( M=\sum\frac{R_t+I_t(1-T)}{(1+r)^t} \) | \( M \), \( R_t \), \( I_t \), \( T \) | Coût dette | Ajuster pour frais/primes |
| Annuité constante | \( A=\frac{Mi}{1-(1+i)^{-n}} \) | \( M \), \( i \), \( n \) | Tableau | Fin de période |
| Amortissements | \( R_{t+1}=R_t(1+i) \) | – | Contrôle | Annuités constantes |
| Amort. constant | \( A_{t+1}-A_t=-\frac{M}{n}i \) | – | Tableau | – |
| Crédit-bail | \( I=\sum\frac{(1-T)L_t+TD_t}{(1+r)^t}+\frac{VR}{(1+r)^n} \) | \( L \), \( D_t \), \( VR \) | Coût du leasing | – |
| CMPC | \( K_e\frac{CP}{CP+D}+K_d(1-T)\frac{D}{CP+D} \) | \( K_e \), \( K_d \), \( T \) | Taux DCF / VAN | Valeurs de marché |
| Coût marginal (livre) | \( \frac{\Delta\text{ coût total}}{\Delta\text{ capital}} \) | – | Financement additionnel | Complément |

---

## 9. Questions de révision

**A. Définition**

1. Définissez le coût du capital. Pourquoi ne faut-il pas le confondre avec le coût des capitaux propres ?
2. Citez les trois usages du coût du capital selon le cours.
3. Qu'est-ce que le β d'exploitation ?
4. Qu'est-ce qu'un taux actuariel net après impôt ?
5. Définissez le contrat de crédit-bail.

**B. Compréhension**

6. Pourquoi la rémunération des actionnaires n'est-elle pas déductible, contrairement aux intérêts ?
7. Pourquoi les pondérations du CMPC doivent-elles être en valeurs de marché ?
8. Dans quels cas l'inverse du PER donne-t-il le coût des fonds propres ?
9. Pourquoi la condition \( k>g \) est-elle indispensable ?
10. Pourquoi le crédit-bail a-t-il un coût implicite ?

**C. Comparaison**

11. Comparez Fisher et Gordon-Shapiro.
12. Comparez annuités constantes et amortissement constant.
13. Comparez la composante explicite et la composante implicite du coût du crédit-bail.

**D. Interprétation**

14. Si l'endettement augmente, que se passe-t-il pour le β fonds propres et la prime de risque financier ?
15. Un emprunt a un taux nominal de 8 % et un taux actuariel de 8,97 % : comment l'expliquer ?
16. Un projet a un TRI inférieur au CMPC : conclusion ?

**E. Calculs**

17. \( P_0=200 \), \( D_0=8 \), \( g=3\% \). Calculer \( k \).
18. \( R_f=3\% \), \( R_M=8\% \), \( \beta=1{,}2 \), \( D/CP=0{,}5 \), \( t=30\% \). Calculer \( K_e \), \( \beta_a \) et les deux primes.
19. Emprunt de 50 000, 4 ans, 6 %, annuités constantes : calculer \( A \) et le tableau.
20. CP = 600, D = 400 (valeurs de marché), \( K_e=10\% \), \( K_d=5\% \), \( T=30\% \). Calculer le CMPC.
21. Dividendes qui triplent en 8 ans, \( D_0=2 \), \( k=15\% \) : prix de l'action ?

**F. Type examen**

22. Une société cotée à 90 verse 6 € (constant) ; calculer \( k \) ; puis \( D_0=6 \), \( g=5\% \) : recalculer. Commenter.
23. Un emprunt in fine de 100 000 sur 4 ans à 7 % avec 2 % de frais : écrire l'équation du coût et la méthode de résolution.

### Réponses

1. Taux de rentabilité minimum que doivent dégager les investissements pour satisfaire actionnaires et créanciers ; c'est le CMPC, dont le coût des FP n'est qu'une composante.
2. (i) taux de référence pour comparer le TRI ; (ii) choix de la structure optimale ; (iii) prix dans les secteurs réglementés.
3. Composante du risque systématique dépendant uniquement de la rentabilité d'exploitation, indépendante du financement (β économique).
4. Taux qui égalise le montant emprunté et la valeur actualisée des remboursements et frais financiers après impôt (et frais).
5. Location avec option d'achat à un prix fixé d'avance, sur bien meuble ou immeuble ; mode de financement substituable à l'emprunt.
6. Elle est aléatoire, versée après paiement de l'impôt sur le résultat ; les intérêts sont contractuels et déductibles.
7. Car ils reflètent ce que chaque source apporterait aujourd'hui (valeur actualisée des flux) ; le comptable est historique.
8. Croissance nulle ; ou \( b=0 \) ; ou \( r=K \).
9. Sinon la somme ne converge pas / \( P_0 \) infini ou négatif.
10. Car l'entreprise perd les économies d'impôt sur les dotations aux amortissements (\( T\cdot D_t \)).
11. Fisher : dividendes constants (ou cession) ; Gordon : croissance \( g \) constante à l'infini, \( k=D_1/P_0+g \).
12. Voir section 2.2.1.2 : annuités décroissantes vs constantes ; amortissements constants vs croissants de raison \( 1+i \).
13. \( (1-T)L_t \) est un décaissement réel après impôt ; \( T\cdot D_t \) est un manque à gagner fiscal.
14. \( \beta \) et prime financière augmentent, \( K_e \) aussi.
15. Frais d'émission/dossier : on reçoit moins que le nominal, donc le coût effectif est plus élevé.
16. Rejet (rentabilité insuffisante pour rémunérer le capital).
17. \( D_1=8{,}24 \) ; \( k=8{,}24/200+3\%=7{,}12\,\% \).
18. \( K_e=3+1{,}2\times5=9\,\% \) ; \( \beta_a=1{,}2/(1+0{,}7\times0{,}5)=0{,}889 \) ; prime d'exploitation \( =0{,}889\times5=4{,}44\,\% \) ; prime financière \( =4{,}44\times0{,}35=1{,}56\,\% \) ; total 6 % ✔.
19. \( A=50\,000\times0{,}06/(1-1{,}06^{-4})=14\,429{,}57 \) ; intérêts an 1 : 3 000 ; amort. 11 429,57 ; etc.
20. \( 0{,}6\times10+0{,}4\times5\times0{,}7=6+1{,}4=7{,}4\,\% \).
21. \( g=3^{1/8}-1=14{,}72\,\% \) ; \( D_1=2\times1{,}1472=2{,}294 \) ; \( P_0=2{,}294/(0{,}15-0{,}1472)\approx 817 \) — **résultat très sensible car \( k \) est presque égal à \( g \)** (illustre la fragilité du modèle).
22. \( k=6/90=6{,}67\,\% \) ; puis \( D_1=6{,}3 \), \( k=7+5=12\,\% \). Commentaire : la croissance relève fortement le coût.
23. Montant reçu \( =100\,000\times0{,}98=98\,000 \) ; flux : 7 000 (ans 1-3), 107 000 (an 4) ; \( 98\,000=\sum 7\,000/(1+r)^t+100\,000/(1+r)^4 \) ; résoudre \( r \) (TRI), qui sera > 7 %.

---

## 10. Liste de contrôle finale

- [ ] Je sais définir le coût du capital et ses trois usages.
- [ ] Je distingue coût du capital et coût des FP.
- [ ] Je sais pourquoi les FP coûtent plus que la dette (non contractuel, non déductible, risque).
- [ ] Je maîtrise Fisher et Gordon-Shapiro (\( D_0 \) vs \( D_1 \), \( k>g \)).
- [ ] Je sais utiliser \( r=B/P_0 \) et la formule de Charreaux.
- [ ] Je connais le MEDAF et sais décomposer \( \beta \) et la prime de risque.
- [ ] Je sais construire les trois tableaux d'amortissement.
- [ ] Je sais calculer un taux actuariel avec frais, avec/sans impôt.
- [ ] Je sais évaluer le coût d'un crédit-bail (explicite + implicite + VR).
- [ ] Je sais calculer le CMPC avec valeurs de marché et dette après impôt.
- [ ] Je sais rédiger une conclusion d'interprétation pour chaque calcul.

---

## 11. Points incertains ou à vérifier

**Pages non fournies / limites de lecture**

- Le chapitre fourni s'arrête à la page 15 (Applications 12 et 13). **S'il existe des pages 16 et suivantes, elles ne sont pas dans ce cours.**
- Pages 1 à 4 lues dans le premier lot de photos ; pages 5 à 15 lues dans le deuxième lot et le premier lot (les doublons ont servi de contrôle).
- Les photos sont parfois floues (pages 5-6 et 9) ; les passages concernés sont signalés ci-dessus.

**Formules dont la lecture est incertaine**

- Page 3 : la forme finale de la somme de Gordon-Shapiro (voir 2.1.1.1) : j'ai conservé la conclusion \( k=D_1/P_0+g \).
- Page 6 : \( PER=\frac{1-b}{r(1-b)}=\frac1r \) (lecture cohérente avec \( r=K \)).
- Page 13 : le taux d'actualisation du crédit-bail est écrit \( r \) sans légende.

**Erreurs apparentes dans le support du professeur**

- Application 7 : intérêt de l'année 4 (3 800 au lieu de 3 200) ; total des amortissements (20 000 au lieu de 100 000).
- Application 12 : l'énoncé ne donne ni \( K_d \) ni \( T \) : CMPC non calculable sans hypothèse.

**Hypothèses de calcul que j'ai posées (à confirmer avec ton professeur)**

- App. 2 : intérêts calculés sur la dette de fin d'année ; dividendes versés en fin d'année.
- App. 6 Q3 : \( B=80 \) conservé.
- App. 7 Q3 : commissions de 2 500 en plus des frais de dossier.
- App. 10 : frais non déductibles ; colonne « Annuité (A+I) » = flux amortissement + intérêt après impôt.
- App. 11 : amortissement linéaire de 200 par an.
- App. 13 : coût de la dette = 4,8 % (coût actuel d'endettement), dette valorisée à 3,8 M€.

**Divergences entre sources**

- CMPC : professeur avec \( (1-T) \), livre sans (voir 6.4).

**Non vérifié**

- Les références bibliographiques (Vernimmen, Charreaux) sont citées comme dans le cours, sans vérification.
- Les corrections des Applications 1 à 13 ne viennent pas du professeur : ce sont mes calculs (recalculés par programme).
