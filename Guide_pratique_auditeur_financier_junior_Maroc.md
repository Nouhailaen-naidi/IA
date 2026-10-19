# Guide pratique de l'auditeur financier junior — Maroc

> Manuel opérationnel pour un stagiaire PFE en cabinet d'audit : quoi faire, dans quel ordre, avec quels documents, comment interpréter et comment documenter.

---

## 0. Lire ce guide

### 0.1 Repères utilisés dans tout le document

| Repère | Signification |
|---|---|
| 📘 **BAO** | *La Boîte à outils de l'auditeur financier*, 3e éd. 2022 (France). Citée « BAO o.N, PDF p.X » (N = numéro d'outil ; X = page du fichier PDF, page de début de l'outil) |
| 📗 **DSCG** | *DSCG 4, Comptabilité et audit*, Obert & Mairesse, Dunod, 2e éd. (France). Citée « DSCG p.X » en **page imprimée** (page du fichier PDF = X + 14) |
| 📙 **SUPPORT** | *Cours 1 : support Audit comptable et financier* (49 p.), contexte **marocain** (loi 17-95, OEC, CGNC), page imprimée |
| 📕 **ISO** | Diaporama *Concepts et principes fondamentaux d'audit* (ISO 19011 / 27007, 26 p.). Il traite l'audit de **systèmes de management**, pas l'audit financier : utilisé uniquement pour les principes généraux de preuve |
| 🧠 | Pratique usuelle de cabinet ou synthèse **hors PDF** : à adapter aux instructions du senior et à la méthodologie du cabinet |
| 🇲🇦✔ | Information marocaine **trouvée en ligne** dans des sources secondaires (cabinets, sites professionnels), pas dans un texte officiel : à confirmer |
| ⚠️ | Référence **française** à ne pas transposer automatiquement au Maroc |
| ❗À vérifier | « **À confirmer dans une source officielle marocaine en vigueur** » (OEC, BO/SGG, DGI, CNSS) |

### 0.2 Sources réellement exploitées

| Fichier fourni | Statut | Utilisation |
|---|---|---|
| `la-boite-a-outils-de-l-auditeur-financier-ed-3…compressed(.pdf et _1.pdf)` | **Même fichier (empreintes identiques)**, 345 p., texte lisible | Source technique principale (outils 7 à 58) |
| `ilide_info-comptabilite-et-audit-manuel-et-applications-2ed…` | 639 p., texte lisible | Chapitres 6 et 7 (audit, contrôle interne : p. imprimées 400 à 548) : démarche, risques, seuil, confirmation, inventaire, sondages, contrôle interne |
| `ilide_info-cours-1-support-audit-comptable-et-financier…` | 49 p., texte lisible | Cadre marocain, QRPE, seuil, plan de mission, rapport |
| `ilide_info-5-concepts-et-principes-fondamentaux-dx27audit…` | 26 p., diaporama | Types et fiabilité des preuves (p. 18 à 26) |
| `document__4_.pdf` | **Inexploitable** : ce n'est pas un PDF mais une page HTML du site de téléchargement (16 Ko, aucun contenu d'audit) | **Non utilisé** |

### 0.3 Limites à connaître

- Dans la BAO, **les pages 120 à 125** (suite du calcul des seuils) sont **vides** dans le fichier ; les pages 164, 204 et 239 n'ont pas de texte extractible et n'ont pas été vérifiées visuellement. Les outils 12, 14, 15 (communication), 37 (R&D), 46 (écarts de conversion) et le Dossier 8 (consolidation) n'ont pas été exploités en détail. Le DSCG n'a été exploité que sur ses chapitres d'audit et de contrôle interne (ch. 6 et 7) ; les corrigés d'applications n'ont pas été repris.
- Les compléments marocains en ligne proviennent de sources secondaires. **Aucun texte de loi n'a été lu dans sa version officielle.**
- Où les sources se contredisent, la divergence est signalée (partie 2.6, 5, 11).

### 0.4 Règle de lecture

> **Tu exécutes, tu documentes, tu remontes. Tu ne décides pas** seul d'un ajustement, d'un niveau de seuil, ni de l'opinion d'audit : ce sont le senior, le manager et le commissaire aux comptes (CAC) qui décident.

---

## Sommaire

1. Comprendre le travail d'un auditeur financier junior
2. Préparer et organiser une mission
3. Comprendre les risques et le contrôle interne
4. Les 20 techniques d'audit à maîtriser
5. Les cycles comptables : guides détaillés (A à I)
6. Analyse financière et clôture des comptes
7. Documentation et communication professionnelle (modèles)
8. Anomalies, ajustements et synthèse
9. Banque de questions d'entretien
10. Checklist des procédures à savoir expliquer et exécuter
11. Connaissances à mémoriser
12. Points réglementaires marocains restant à vérifier
13. Sources PDF et références de pages

---

# PARTIE 1 — Comprendre le travail d'un auditeur financier junior

## 1.1 Le rôle de l'auditeur et l'objectif de la mission

**Définition à retenir.** L'audit financier externe est un examen professionnel, indépendant et documenté des états financiers, pour exprimer une **opinion** sur leur **régularité**, leur **sincérité** et l'**image fidèle** qu'ils donnent du patrimoine, de la situation financière et des résultats. 📙 SUPPORT p.4, 6, 10 ; 📗 DSCG p.438-439

- **Assurance raisonnable, non absolue** : le CAC est tenu d'une **obligation de moyens, pas de résultat** ; il travaille par sondages et n'a pas à rechercher toutes les erreurs. 📙 SUPPORT p.11
- Au Maroc, la loi sur les sociétés anonymes assigne au CAC une mission permanente de vérification des valeurs, livres et documents comptables, de conformité de la comptabilité, de concordance du rapport de gestion avec les états de synthèse et de respect de l'égalité entre actionnaires, **sans immixtion dans la gestion**. 📙 SUPPORT p.10-11 (cite les art. 166, 169, 175 de la loi sur les SA ; ❗À vérifier sur le texte officiel)

## 1.2 Audit externe, audit interne, contrôle interne, contrôle de gestion

| | Audit externe (CAC) | Audit interne | Contrôle interne | Contrôle de gestion |
|---|---|---|---|---|
| **Qui** | Professionnel indépendant, nommé par l'AGO | Salarié de l'entreprise | Direction et tous les collaborateurs | Service interne |
| **Objectif** | Opinion sur les états financiers | Apprécier la maîtrise des opérations, recommander | Prévenir et détecter erreurs et fraudes, protéger les actifs, fiabiliser l'information | Piloter la performance : budgets, écarts, tableaux de bord 🧠 |
| **Destinataire** | Actionnaires, tiers | Direction | Direction | Direction |
| **Périodicité** | Annuelle (et semestrielle selon mission) | Permanente, selon un plan | Permanente | Permanente |
| **Résultat** | Rapport : certification avec ou sans réserve, ou refus | Recommandations et suivi | Procédures et contrôles | Reporting |

Sources : 📙 SUPPORT p.5-9 (tableau comparatif audit interne/externe), p.44-46 (contrôle interne) ; contrôle de gestion 🧠.

**Distinction à retenir** : l'auditeur externe **s'appuie** sur le contrôle interne (il l'évalue) mais **ne le conçoit pas** ; le CAC n'a pas le droit de réaliser les documents qu'il contrôle et ne peut être à la fois expert-comptable et CAC de la même société. 📙 SUPPORT p.10 (note 1)

## 1.3 Les rôles dans l'équipe

| Rôle | Ce qu'il fait | Limite pour toi |
|---|---|---|
| **Stagiaire / assistant** | Exécute des tests délimités, prépare les feuilles de travail, rédige ses constats | Ne conclut pas seul sur un compte significatif ; alerte |
| **Senior / chef de mission** | Planifie, répartit, supervise, revoit, discute avec le client | C'est lui qui valide ta conclusion |
| **Manager** | Pilote la qualité et la relation client, arbitre les points sensibles | Tu lui parles via le senior |
| **Commissaire aux comptes** | Seul à signer le rapport, **conserve la responsabilité des travaux délégués**, supervise | Il décide de l'opinion |

📙 SUPPORT p.11 (délégation : le CAC reste responsable) ; 📘 BAO o.13, PDF p.74 (supervision) ; 🧠 pour la description des grades.

## 1.4 Le déroulement d'une mission annuelle

| Étape | Contenu | Tes tâches typiques |
|---|---|---|
| **0. Acceptation** | Faisabilité, indépendance, lettre de mission | Rien (senior/CAC) ; consulter la lettre pour connaître le périmètre |
| **1. Orientation et planification** | Prise de connaissance, revue analytique, zones de risque, **seuil de signification**, plan de mission | Mettre à jour le dossier permanent, remplir le QRPE, calculer les variations N/N-1 |
| **2. Évaluation du contrôle interne** | Compréhension, évaluation de la conception, tests de fonctionnement | Décrire un processus, faire un test de cheminement, tester un échantillon |
| **3. Contrôle des comptes** | Tests de substance par cycle | Circularisations, cut-off, rapprochements, inventaire, sondages |
| **4. Synthèse et rapport** | Événements postérieurs, lettre d'affirmation, revue, rapport | Finaliser tes feuilles, répondre aux points de revue |

📙 SUPPORT p.20-49 (étapes préliminaire, 1, 2, 3, 4) ; 📗 DSCG p.435 (cinq étapes) ; 📘 BAO (Dossiers 2 à 7).

**Vue d'ensemble concrète 🧠 (varie selon cabinet)** : une société anonyme à clôture au 31 décembre est souvent vue en deux passages : une **intervention intermédiaire** (compréhension des processus, tests de contrôle, premiers tests) puis une **intervention finale** après la clôture (cut-off, circularisations, rapprochements bancaires, inventaire des soldes, revue subséquente, lettre d'affirmation). Le calendrier réel est fixé par le plan de mission.

## 1.5 Vérifier une écriture, auditer un solde, auditer un processus

| | Vérifier une écriture | Auditer un solde | Auditer un processus |
|---|---|---|---|
| **Question** | Cette opération est-elle correcte et justifiée ? | Ce compte à la clôture est-il vrai, complet, bien évalué ? | Le dispositif empêche-t-il ou détecte-t-il les erreurs ? |
| **Méthode** | Remonter à la pièce (date, montant, imputation, autorisation) | Tests de détail, confirmations, procédures analytiques | Compréhension, test de cheminement, test de fonctionnement du contrôle |
| **Résultat** | Anomalie ponctuelle | Conclusion sur le poste (et ajustement éventuel) | Conclusion sur le risque lié au contrôle |

## 1.6 La logique fondamentale : risque → assertion → procédure → preuve → conclusion

| Maillon | Question | Exemple « Clients » |
|---|---|---|
| **Risque** | Qu'est-ce qui peut être faux ? | Vente fictive ou anticipée ; créance irrécouvrable |
| **Assertion** | Quel critère est menacé ? | Existence, évaluation, séparation des exercices |
| **Procédure** | Que fait-on ? | Circularisation, cut-off ventes, balance âgée |
| **Preuve** | Quel élément probant ? | Confirmation du client, bon de livraison, encaissement post-clôture |
| **Conclusion** | Que peut-on dire ? | « Créances existantes et recouvrables à hauteur de… » ou « anomalie de X » |

**Hiérarchie de la fiabilité des preuves** (📕 ISO p.18-26, adaptée à l'audit financier 🧠) : la preuve **orale** est la moins fiable ; puis **documentaire** (interne < externe), **analytique**, **technique**, **confirmative** (tiers indépendant), enfin **physique** et **mathématique** (réalisées par l'auditeur lui-même). Principe pratique : *plus une preuve vient d'une source externe, indépendante et obtenue directement, plus elle pèse*.

**Principes de conduite (ISO 19011, valables pour tout auditeur)** 📕 p.10-16 : déontologie, présentation impartiale (consigner aussi les obstacles et les désaccords), conscience professionnelle, **confidentialité**, indépendance, approche **fondée sur la preuve** (les constats reposent uniquement sur des preuves vérifiables). Les règles propres au CAC marocain (indépendance, incompatibilités) sont en partie 12.

---

# PARTIE 2 — Préparer et organiser une mission

## 2.1 Prendre connaissance du dossier client

**Objectif.** Comprendre l'entreprise avant de tester quoi que ce soit.

**Documents** : dossier permanent (DP), lettre de mission, plan de mission et note de synthèse de l'exercice précédent, rapports CAC antérieurs, états de synthèse N-1 (au moins 3 exercices), statuts, PV d'assemblées, organigramme, manuel de procédures. 📙 SUPPORT p.34-35 ; 📘 BAO o.7, PDF p.50

**Étapes**
1. Lire la **note de synthèse N-1** : points d'audit, ajustements, suspens, faiblesses de contrôle interne.
2. Lire le **plan de mission** : seuils, comptes significatifs, programme, calendrier.
3. Ouvrir le **DP** : structure juridique, actionnariat, contrats pluriannuels, PV.
4. Compléter ou mettre à jour le **questionnaire de revue préliminaire de l'environnement (QRPE)** (voir ci-dessous).
5. Noter toute nouveauté (acquisition, nouveau financement, changement de méthode, litige) et la signaler au senior.

**QRPE : rubriques à couvrir** 📙 SUPPORT p.26-33 : environnement général et sectoriel ; concurrence ; stratégie et gouvernance ; investissements et R&D ; patrimoine et stocks (lieux, stocks chez les tiers) ; clients et fournisseurs (concentration, dépendance) ; force commerciale ; situation financière (banques, covenants, change) ; environnement de contrôle et d'organisation ; système d'information ; environnement d'audit (raison du changement de CAC, audit interne, manuel de procédures) ; règles et méthodes comptables (ajustements fréquents, modification tardive des comptes, pression sur le résultat) ; structure juridique ; politique sociale (redressement CNSS, litiges sociaux).

**Résultat attendu** : DP à jour + note courte des risques perçus, remise au senior.

**Trace d'audit** : date de mise à jour du DP, sources consultées, nouveautés relevées.

## 2.2 Récupérer les états financiers, la balance, le grand livre et les documents de clôture

**Documents à obtenir** (liste de demandes, modèle partie 7.2) : balance générale N et N-1 ; **grand livre** ; balances auxiliaires clients et fournisseurs ; états de synthèse N (bilan, compte de produits et charges, tableaux annexes) ; états de rapprochement bancaire ; tableaux de variation (immobilisations, provisions, capitaux propres) ; inventaire des stocks ; liste des écritures d'inventaire et d'OD ; déclarations fiscales et sociales.

**Conseil** 🧠 : demander **le même format chaque année** (ça facilite le rapprochement N/N-1) et conserver la copie des fichiers reçus, avec date et nom de l'interlocuteur.

## 2.3 Récupérer l'exercice précédent et vérifier l'ouverture

1. Obtenir les **comptes N-1 audités** (états de synthèse certifiés).
2. Rapprocher les **soldes d'ouverture N** de la balance avec les **soldes de clôture N-1 audités** (poste par poste).
3. Toute différence = anomalie d'ouverture : la remonter immédiatement (c'est un risque d'intangibilité du bilan d'ouverture).

📘 BAO o.23, PDF p.127 (le tableau de passage part du solde audité N-1) ; 📙 SUPPORT p.17 (intangibilité du bilan d'ouverture).

## 2.4 Rapprocher états financiers, balance et comptes

Voir **technique T1** (partie 4). C'est la première feuille de travail que tu produis.

## 2.5 Identifier les variations importantes entre N et N-1

**Étapes**
1. Reprendre la balance N et N-1 dans un tableur ; calculer pour chaque compte et chaque poste : **écart en valeur** et **écart en %**.
2. Appliquer le **seuil d'investigation** donné par le senior (ex. variations > 15 % et > X MAD).
3. Pour chaque variation retenue, **formuler une attente avant de demander l'explication** (activité, effectifs, prix, investissements). 📘 BAO o.55-57
4. Demander l'explication au client, **la vérifier** par un document, puis conclure (voir partie 6 et modèle 7.7).

📙 SUPPORT p.36-38 liste les postes qui suscitent le plus de questions : capitaux propres, réserves, résultat, emprunts, immobilisations, amortissements, stocks, fournisseurs, clients, clients douteux, provisions, banque, caisse.

## 2.6 Comprendre le seuil de signification et les comptes significatifs (ce que tu dois savoir, sans le fixer)

Le seuil est **fixé par le senior/CAC** ; tu dois comprendre pourquoi un test est dimensionné ainsi.

| Source | Critères et taux | Remarque |
|---|---|---|
| 📘 BAO o.22, PDF p.118 (note CNCC XXI, juillet 2021, ⚠️ France) | Résultat courant avant impôts et résultat net : 3 à 10 % ; CA : 0,5 à 3 % ; EBITDA : 2 à 6 % ; endettement net : 1 à 2 % ; charges : 0,5 à 3 % ; holdings (total bilan 0,5 à 3 %, capitaux propres 1 à 5 %, jusqu'à 10 %) ; but non lucratif : revenus bruts ou charges 0,5 à 2 % | Taux plus bas si le risque d'audit est plus élevé. Les pages suivantes de l'outil sont vides dans le PDF |
| 📗 DSCG p.445-448 (⚠️ France) | Constatation significative si elle touche l'actif net ou le bénéfice net après impôt de 5 à 10 %, ou une rubrique du bilan de plus de 10 % | Exemple : bénéfice 800 k€ × 5 % = **40 k€**, et seuil de 10 % de la rubrique « Provisions » (200 k€) = **20 k€** |
| 📙 SUPPORT p.40-42 (contexte marocain) | Résultat courant avant impôt : 5 à 10 % ; CA : 0,5 à 1 % ; capitaux propres : 1 à 2 % ; actif total : 0,5 à 1 % (le texte indique aussi « 5 % à 1 % », incohérence interne) ; moyenne sur 4 exercices ; l'**erreur tolérable** = SDS × un pourcentage défini par le **manuel du cabinet** (exemple : 60 % à 75 %) | Exemple : SDS 100 kDh × 60 % = **60 kDh** d'erreur tolérable ; les comptes au-dessus sont « significatifs » |

**Divergence signalée** : les trois sources ne donnent pas les mêmes fourchettes. Au Maroc, **applique les taux et le manuel de ton cabinet** ; les autres ne servent qu'à comprendre. ❗À vérifier : tout seuil ou taux officiel.

**Comptes et assertions significatifs** 📘 BAO o.17, PDF p.93 : un compte est significatif s'il dépasse le seuil **ou** si sa nature le rend risqué (estimations, complexité, fraude). Actif → **existence + évaluation** ; passif → **exhaustivité + évaluation**. Un compte à solde nul peut être significatif (ex. provision pour litige inexistante alors qu'un litige existe).

## 2.7 Feuilles de travail, feuille maîtresse, référencement

**Feuille maîtresse** 📘 BAO o.9, PDF p.58 : une par section (ex. immobilisations), détail par compte N / N-1, base des tests, des revues analytiques et du référencement.
1. Créer à partir de la balance N et N-1 (vérifier que la colonne N-1 = comptes audités).
2. Référencer chaque ligne vers la feuille de travail qui l'explique.
3. Vérifier que chaque compte a une référence **ou** est marqué « non significatif ».

**Feuille de travail** 📘 BAO o.10, PDF p.62 : objectif → travaux → résultats → conclusion (modèle partie 7.1).

**Référencement croisé** 📘 BAO o.8, PDF p.54 : toute feuille est référencée (en haut à droite) ; une feuille non référencée **ne fait pas partie du dossier**. Le référencement fonctionne **dans les deux sens** (descendant et remontant) et matérialise la piste d'audit.

## 2.8 Programme de travail

**Définition.** Document qui liste, par section, les procédures à réaliser, les répartit et sert de support de supervision. Il est défini **après** l'évaluation des risques. 📘 BAO o.11, PDF p.66 ; 📗 DSCG p.449-450

**Ce que tu fais**
1. Récupérer le programme de ta section auprès du senior.
2. Pour chaque ligne : réaliser, documenter, référencer, cocher.
3. Si une procédure est **inadaptée** à l'entreprise (ex. autre méthode de valorisation), **ne la supprime pas** : propose au senior une adaptation et documente la raison.

Le programme est un guide, pas un carcan : si tes constats l'exigent, tu alertes le senior pour étendre les travaux. 📘 BAO o.11

> Le DSCG indique que le temps de planification représente en moyenne environ **10 %** du temps total de la mission. 📗 DSCG p.450 (🧠 repère indicatif)

## 2.9 Récapitulatif de la préparation

| Étape | Documents | Action | Résultat attendu |
|---|---|---|---|
| Dossier client | DP, N-1, plan, note de synthèse | Lire, mettre à jour | DP à jour |
| Demande de pièces | Liste PBC | Envoyer et suivre | Pièces reçues, tracées |
| Ouverture N | Comptes N-1 audités | Rapprocher | Ouverture validée |
| Rapprochement | Balance, GL, états | T1 | Feuille T1 |
| Variations | Balance N/N-1 | Calculer, interroger | Fiches de variation |
| Feuilles | Balance | Maîtresses + travail | Dossier structuré |
| Programme | Programme du senior | Exécuter | Travaux référencés |

---

# PARTIE 3 — Comprendre les risques et le contrôle interne

> **Trois étapes à ne jamais confondre** (📗 DSCG p.531-534, 📙 SUPPORT p.44-46, 📘 BAO o.19, PDF p.103)
>
> | Étape | Question | Livrable |
> |---|---|---|
> | **1. Compréhension** | Comment le processus fonctionne-t-il réellement ? | Description + test de cheminement |
> | **2. Évaluation de la conception** | Si le contrôle fonctionne, empêche-t-il ou détecte-t-il l'erreur ? | Tableau forces/faiblesses |
> | **3. Test du fonctionnement** | A-t-il fonctionné **toute la période** ? | Résultat de test sur échantillon |

**Pourquoi c'est utile** 📙 SUPPORT p.46 : une pièce justificative donne la preuve **directe** de la réalité d'une opération ; le contrôle interne donne une preuve **indirecte** que **toutes** les opérations sont correctement enregistrées. L'évaluation du contrôle interne ne s'applique qu'aux **opérations répétitives**.

## 3.1 Comprendre un processus opérationnel

**Cinq techniques de prise de connaissance** 📗 DSCG p.534-542

| Technique | Quand l'utiliser | Limite |
|---|---|---|
| **Documents existants** : organigramme, description de postes, manuel de procédures, circuit des documents, rapports d'audit interne, dossier de l'exercice précédent | Toujours en premier | Le document décrit la théorie, pas la pratique |
| **Conversation d'approche** (entretien libre) | Petite entité ; premier contact | Difficile à synthétiser si l'entité est grande |
| **Diagramme de circulation** (qui fait quoi, quel document, dans quel ordre) | Processus avec plusieurs services | Demande du temps ; éviter trop de symboles |
| **Questionnaire** (fermé oui/non ou ouvert) et **guide opératoire** | Pour ne rien oublier | Adapter les listes types à l'entreprise |
| **Grille d'analyse** (tableau opérations × personnes) | Repérer les **cumuls de fonctions** | Ne montre pas la qualité d'exécution |

**Étapes pratiques**
1. Demander le manuel de procédures et l'organigramme ; à défaut, un organigramme détaillé. 📙 SUPPORT p.35
2. Identifier le processus à comprendre (ex. achats-fournisseurs, ventes-clients, paie) et son **propriétaire**.
3. Faire un entretien avec **la personne qui exécute** (pas seulement son chef) : « Racontez-moi ce qui se passe quand… ».
4. Noter les documents créés ou utilisés à chaque étape, les systèmes utilisés, les autorisations.
5. Restituer par écrit au responsable pour **confirmer ta compréhension**.

## 3.2 Décrire un processus de manière simple

Utilise un tableau en 5 colonnes (modèle réutilisable) :

| # | Étape | Qui | Document / système | Contrôle en place |
|---|---|---|---|---|
| 1 | Besoin exprimé | Service demandeur | Demande d'achat | Signature d'un habilité |
| 2 | Commande | Acheteur | Bon de commande numéroté | Visa du responsable |
| … | … | … | … | … |

Règles : une ligne = une action ; un document = un nom précis ; une personne = une **fonction** (pas un prénom) ; signaler en note tout point **non clair**.

## 3.3 Identifier les risques d'erreur ou de fraude

**Méthode** : pour **chaque étape**, pose trois questions : *Qu'est-ce qui peut être oublié ? Qu'est-ce qui peut être faux ? Qu'est-ce qui peut être détourné ?* Relie le risque à l'**assertion** concernée (exhaustivité, réalité, mesure, séparation des exercices, classification).

Objectif du contrôle interne sur les flux significatifs 📙 SUPPORT p.46-47 : toutes les opérations enregistrées (exhaustivité) ; chaque opération réelle, correctement évaluée, enregistrée dans la bonne période et correctement imputée ; correctement totalisées et centralisées.

**Indices de risque de fraude à connaître** 📘 BAO o.21, PDF p.114 : pression sur le résultat, dirigeant dominant, écritures manuelles inhabituelles, montants ronds, libellés « divers », rapprochements bancaires non justifiés. **Présomption de risque sur la comptabilisation des produits.**

## 3.4 Identifier les contrôles existants et évaluer leur conception

**Typologie** 📗 DSCG p.548 : contrôle **préventif** (a priori, ex. mot de passe) ou **de détection** (a posteriori, ex. rapprochement) ; **manuel** ou **programmé** (automatique) ; **bloquant** ou simple alerte.

**Grille d'évaluation de la conception** 🧠 (à remplir pour chaque contrôle)

| Critère | Question |
|---|---|
| Pertinence | Le contrôle couvre-t-il **le risque identifié** et l'assertion concernée ? |
| Précision | Le contrôle porte-t-il sur 100 % des opérations ou sur une partie ? Quel seuil ? |
| Indépendance | La personne qui contrôle est-elle **différente** de celle qui exécute ? (séparation des fonctions) |
| Traçabilité | Y a-t-il une **preuve écrite** (visa, signature, état d'exception, log) ? |
| Réaction | Que se passe-t-il quand le contrôle détecte un écart ? Est-il traité ? |
| Fréquence | Journalier, mensuel, annuel ? (détermine l'échantillon de test) |

**Séparation des fonctions** 📗 DSCG p.542 : autoriser, enregistrer, détenir les actifs et contrôler ne doivent pas être cumulés par la même personne. La grille d'analyse « opérations × personnes » fait apparaître les cumuls.

## 3.5 Documenter un processus, les risques, les contrôles et les faiblesses

**Tableau d'évaluation du système** (inspiré de 📗 DSCG p.543, modèle réutilisable)

| Réf. | Étape / contrôle | Force | Faiblesse | Effet possible | Incidence sur les comptes | Incidence sur les travaux | Recommandation |
|---|---|---|---|---|---|---|---|
| QCI-12 | Réception des marchandises | Bon de livraison conservé | **Pas de bon de réception** | Dette non enregistrée, paiement sans livraison | Exhaustivité des dettes, cut-off | Étendre cut-off et circularisation fournisseurs | Mettre en place un bon de réception |

## 3.6 Réaliser un test de cheminement (walkthrough)

**Définition.** Suivre un **petit nombre** de transactions de bout en bout, de l'origine au dénouement, pour vérifier que le système **décrit** existe réellement. 📗 DSCG p.543-544

**Étapes**
1. Choisir **une transaction de chaque nature** (ex. achat de marchandises, achat de service, avoir fournisseur). Le DSCG indique que le nombre peut être réduit (**trois à cinq** par nature).
2. Prendre le **dossier réel** (commande, réception, facture, paiement).
3. Suivre la transaction à l'endroit où elle est créée, validée, enregistrée, payée ; **observer** l'exécution et poser des questions à l'opérateur.
4. Comparer à ta description ; si ça diffère, **corriger la description**.
5. Noter les références des pièces (n° de facture, de commande, de chèque, de l'état de règlement).

**Exemple (adapté du DSCG)** : facture 12235 ↔ commande 1272 ↔ visa du calcul ↔ opération 2337 ↔ chèque 3634 ↔ état de règlement 212 → chaque ligne « conforme au diagramme » ou **écart noté**.

**Limite importante** 📘 BAO o.19 : un test de cheminement **ne prouve pas** l'efficacité du contrôle ; il confirme la **compréhension**. L'efficacité se prouve par un test sur échantillon (3.7).

## 3.7 Tester le fonctionnement d'un contrôle

**Objectif.** Vérifier que le contrôle a fonctionné **pendant toute la période**. 📗 DSCG p.543-545 (« tests de permanence ») ; 📘 BAO o.19

**Documents** : programme de test du senior, population des opérations de la période, preuves de contrôle (visas, signatures, états d'exception).

**Étapes**
1. Définir l'**attribut** à tester (ex. « bon de commande visé par le responsable avant émission »).
2. Définir la **population** et la **fréquence du contrôle**.
3. Prendre l'**échantillon** indiqué par le senior (repères BAO ci-dessous).
4. Pour chaque élément, vérifier l'**attribut** et noter OK / écart.
5. Compter les écarts, déterminer s'il y a une **procédure de remplacement** (contrôle compensatoire) avant de conclure. 📗 DSCG p.544
6. Conclure : efficace / déficient ; mettre à jour l'évaluation du risque lié au contrôle.

**Repères d'échantillon (BAO o.19, PDF p.103, ⚠️ pratique française, à valider avec le cabinet)**

| Fréquence du contrôle | Échantillon |
|---|---|
| Journalier | 25 |
| Hebdomadaire | 5 |
| Mensuel | 2 |
| Trimestriel | 2 |
| Annuel | 1 |
| Applicatif (automatique) | 1, après validation des contrôles généraux informatiques |

**Si erreur** 📘 BAO : contrôle journalier → 1 erreur : extension de 25 à 40 ; 2 erreurs : de 25 à 60 ; au-delà : déficient. Autres fréquences : **une erreur = déficient**. Les travaux de substance doivent alors être **étendus**.

**Contrôle de l'environnement informatique** 📗 DSCG p.545-548 ; 📘 BAO o.33 : si le processus est informatisé, comprendre les applications et interfaces, la gestion des accès, les sauvegardes, la maintenance. Les contrôles **programmés** (automatiques) peuvent alléger les tests si les contrôles généraux informatiques sont fiables ; sinon, tests de substance renforcés. 🧠 Pour un junior : demander les listings d'utilisateurs et les droits, et les transmettre au senior.

## 3.8 Quand faut-il des tests substantifs complémentaires ?

| Résultat de l'évaluation | Conséquence sur les tests de substance |
|---|---|
| Contrôle efficace (RC faible) | Programme **minimum** : analytique + tests de détail limités 📙 SUPPORT p.47 |
| Contrôle déficient, absent ou non testé (RC élevé) | **Renforcer** : plus de sondages, seuils d'investigation plus bas, travaux après la clôture, plus de sites 📗 DSCG p.445 ; 📙 SUPPORT p.47 |
| Risque inhérent élevé | Étendre même si les contrôles sont efficaces |

**Matrice DSCG** (risque de non-détection acceptable, 📗 DSCG p.444) : risque inhérent **élevé** et risque de contrôle **élevé** → RND acceptable **minimum** → travaux **très étendus** ; les deux **faibles** → RND acceptable maximum → travaux allégés.
**Grille BAO du RAS** (📘 o.20, PDF p.110-111) : mêmes combinaisons, lues à l'inverse (maximum quand les deux risques sont élevés). Ce sont deux lectures de la même logique, pas une contradiction.

## 3.9 Signaler une faiblesse au senior

1. **Fais le constat factuel** : ce que tu as observé, avec la pièce ou la référence (« sur 25 factures testées, 4 n'ont pas de visa du responsable des achats »).
2. **Vérifie** s'il existe un contrôle compensatoire avant d'alerter (voir 3.7 étape 5).
3. **Quantifie** si possible (nombre d'écarts, montants concernés).
4. **Distingue** fait / hypothèse (« visa absent » est un fait ; « le contrôle n'est pas réalisé » est une hypothèse à confirmer).
5. **Alerte vite** : oral au senior puis écrit (note) ; la faiblesse peut changer l'étendue des travaux de la **suite** de la mission.
6. Le senior décidera s'il faut l'inclure dans une **lettre de recommandations / de faiblesses** adressée à la direction (le DSCG mentionne l'engagement de remettre à la fin des travaux une lettre résumant les déficiences relevées, 📗 DSCG p.437).

## 3.10 Exemple de cartographie simple : achats → fournisseurs → paiement

> Cas inspiré de 📗 DSCG p.538-543 (société qui fabrique des jouets), adapté (sociétés et chiffres fictifs).

**Situation décrite par le client** : le responsable du magasin commande aux fournisseurs ; **aucun bon de réception** n'est établi, chaque service garde le bon de livraison ; les factures arrivent directement à la comptabilité qui les enregistre et les classe ; les chèques sont préparés par la comptabilité, signés par le dirigeant, **rendus à la comptabilité qui les comptabilise et les envoie**.

| # | Étape | Qui | Document | Risque | Contrôle en place | Preuve attendue (test) |
|---|---|---|---|---|---|---|
| 1 | Commande | Magasinier | Bon de commande | Commande non autorisée, prix non comparé | Aucun visible | Visa sur bon de commande |
| 2 | Livraison | Magasin / services | Bon de livraison (copie conservée par chaque service) | Réception non enregistrée, livraison partielle | **Aucun bon de réception** | Bon de livraison signé |
| 3 | Facturation | Comptabilité | Facture | Facture sans livraison, doublon, mauvaise période | Pointage manuel (si existant) | Facture rapprochée de commande + livraison |
| 4 | Règlement | Comptabilité + dirigeant | Chèque, état de règlement | Paiement sans bon à payer, cumul préparation / comptabilisation / envoi | Signature du dirigeant | Bon à payer, copie de chèque |

**Faiblesses relevées** : (a) pas de bon de réception → risque de **dettes non enregistrées** et de factures sans livraison ; (b) la comptabilité prépare, comptabilise et envoie les chèques → **cumul de fonctions** ; (c) pas de rapprochement systématique commande / livraison / facture.
**Conséquence sur les travaux** : étendre le **cut-off achats**, circulariser davantage de fournisseurs, prévoir une **revue subséquente des décaissements** (techniques T6, T7, T9).
**Remontée** : note au senior avec les références des transactions testées.

---

# PARTIE 4 — Les 20 techniques d'audit à maîtriser

> **Format de chaque fiche** : Objectif · Risque · Documents · Étapes · Exemple · Si une anomalie apparaît · Limites · Trace d'audit · Question d'entretien. Les exemples chiffrés sont **fictifs** (sociétés inventées, montants en MAD) ; ils ne représentent aucun cas réel.
>
> **Règle générale « si une anomalie apparaît »** (valable pour les 20 fiches) : (1) ne corrige pas toi-même ; (2) **quantifie** ; (3) cherche une explication **documentée** (pas seulement orale) ; (4) note le constat sur la feuille avec référence ; (5) informe le senior le jour même si l'anomalie est potentiellement significative (partie 8). Ne conclus **jamais** à la fraude : un écart est une **anomalie à expliquer**.

---

## T1. Rapprochement entre balance, grand livre et états financiers

**Objectif.** S'assurer que les états financiers reflètent exactement la comptabilité. 📘 BAO o.24, PDF p.129

**Risque.** Poste des états qui ne correspond pas aux comptes ; écritures de clôture non reportées ; balance différente de celle finalement utilisée.

**Documents.** Balance générale N et N-1 ; grand livre ; états de synthèse (bilan, compte de produits et charges) ; table de correspondance comptes ↔ postes ; liste des OD de clôture.

**Étapes**
1. Vérifier que la **balance est équilibrée** (total débits = total crédits, en mouvements et en soldes).
2. Vérifier que les **soldes de clôture N-1** de la balance N = comptes **audités** N-1.
3. Obtenir la **table de correspondance** comptes → postes (ne pas la reconstruire seul).
4. Reconstituer chaque poste des états (bilan, CPC) à partir de la balance ; comparer.
5. Pour les comptes significatifs, comparer le **solde de la balance** au **total du grand livre** (soldes et mouvements).
6. Identifier les **écritures postérieures** à l'édition de la balance (OD, régularisations).
7. Investiguer chaque écart, documenter, conclure.

**Exemple.** Poste « Clients et comptes rattachés (net) » du bilan : **4 820 000**. Balance : clients 5 000 000 + clients douteux 320 000 − dépréciations 500 000 = **4 820 000** ✔. Si la balance donnait 4 805 000, l'écart de **15 000** doit être expliqué (ex. OD saisie après l'édition de la balance).

**Si une anomalie apparaît.** Demander la balance définitive et la liste des OD ; informer le senior si l'écart dépasse le seuil d'investigation.

**Limites.** Un rapprochement entre deux documents issus du **même logiciel** est un **bouclage**, pas une preuve de réalité. 📘 BAO o.24

**Trace.** Feuille T1 : références des documents, totaux, écarts, explication, symbole de vérification.

**❓ Question.** *« À quoi sert de rapprocher la balance et les états financiers ? »* **Réponse** : « À vérifier que les états publiés sont bien issus de la comptabilité, sans poste omis ni écriture oubliée. C'est la base sur laquelle s'appuient tous mes tests, mais ce n'est pas une preuve de réalité. »

---

## T2. Vérification d'une écriture comptable

**Objectif.** Vérifier qu'une écriture est **réelle, autorisée, exacte, bien imputée et bien datée**. 📗 DSCG p.455 (inspection des enregistrements)

**Risque.** Écriture fictive ; mauvaise période ; mauvaise imputation ; contournement des contrôles par des **écritures manuelles** (OD), surtout en fin de période. 📘 BAO o.21

**Documents.** Journal / grand livre ; pièce justificative ; justificatif d'autorisation ; contrat ou décision éventuelle.

**Étapes**
1. **Sélectionner** : OD manuelles, écritures de fin de période, montants ronds, libellés vagues (« divers », « régularisation »), contreparties inhabituelles, écritures sans pièce.
2. Retrouver la **pièce** à partir du numéro de pièce.
3. Vérifier **date** (pièce vs comptabilisation → exercice), **montant** (HT, taxe, TTC), **tiers**, **comptes débité et crédité**.
4. Vérifier l'**autorisation** (qui a saisi, qui a validé).
5. Juger la **cohérence économique** : la nature de l'opération justifie-t-elle ce compte ?
6. Conclure sur l'écriture et référencer.

**Exemple.** OD du 31/12/N : Débit « Autres débiteurs » **480 000** / Crédit « Autres produits », libellé « régularisation », aucune pièce. → **Demander** le justificatif et l'explication écrite ; si rien n'est fourni, **suspens** à remonter immédiatement. Ce n'est pas une fraude avérée : c'est une écriture non justifiée.

**Si une anomalie apparaît.** Écriture sans pièce : suspens + alerte ; mauvaise imputation : proposer un reclassement ; mauvaise période : renvoi à T7.

**Limites.** Tester une écriture ne prouve rien sur les autres : l'échantillon dépend de ton critère de sélection.

**Trace.** N° d'écriture, date, montant, pièce examinée (référence), anomalie, conclusion.

**❓ Question.** *« Quelles écritures regardez-vous en priorité ? »* **Réponse** : « Les écritures manuelles de fin de période, les montants ronds, les libellés vagues et celles passées par des personnes inhabituelles : ce sont les plus exposées au contournement des contrôles. »

---

## T3. Contrôle d'une facture et de ses pièces justificatives

**Objectif.** Vérifier qu'une facture correspond à une opération **réelle** et qu'elle est **correctement comptabilisée**.

**Risque.** Facture fictive, doublon, montant faux, mauvaise période, fournisseur ou client non autorisé.

**Documents.** Facture ; bon de commande ; bon de livraison ou de réception ; contrat ; preuve de paiement ou d'encaissement.

**Étapes**
1. Vérifier l'**identité** de l'émetteur et du destinataire et la **cohérence** avec le tiers comptabilisé.
2. Vérifier le **numéro** (séquence continue), la **date**, la **désignation**, les quantités et prix.
3. **Recalculer** HT, TVA, TTC. 📘 BAO o.25 (vérification arithmétique : lignes et colonnes)
4. Rapprocher des **pièces** (commande, livraison, réception) : voir T4.
5. Vérifier la **période** (date du fait générateur) : voir T7.
6. Chercher les **doublons** (même montant, même tiers, numéros proches).
7. Vérifier le **règlement** (encaissement ou paiement) et son rapprochement.

❗À vérifier : les **mentions obligatoires** d'une facture selon la réglementation marocaine (identifiants fiscaux et commerciaux, ICE, etc.) : ne pas citer sans contrôle.

**Cas pratique 1 — échantillon de factures clients (société fictive « Atlas Emballages SA »)** : 6 factures de décembre sélectionnées, seuil d'investigation 50 000 HT.

| Facture | Date | Client | HT | Commande | Livraison | Encaissement | Résultat |
|---|---|---|---:|---|---|---|---|
| F-1182 | 12/12 | A | 120 000 | ✔ | 12/12 ✔ | 20/01 ✔ | OK |
| F-1187 | 18/12 | B | 95 000 | ✔ | 18/12 ✔ | 05/02 ✔ | OK |
| F-1195 | 22/12 | C | 60 000 | ✔ | 22/12 ✔ | — | À circulariser |
| F-1201 | 30/12 | D | **85 000** | ✔ | **03/01 (N+1)** | — | **Anomalie cut-off** (T7) |
| F-1203 | 31/12 | E | 70 000 | ✔ | 30/12 ✔ | 15/01 ✔ | OK |
| F-1204 | 31/12 | F | 55 000 | ✘ | 31/12 ✔ | — | **Commande manquante** → suspens |

**Conclusion à rédiger** : sur 6 factures testées (485 000 HT), 4 conformes, 1 anomalie de période (85 000), 1 pièce manquante (55 000) : renvoyer au senior pour étendre l'échantillon sur la dernière semaine de décembre.

**Limites.** Une facture est une preuve **interne ou externe selon l'origine** : une facture fournisseur est plus probante qu'une facture émise par l'entité elle-même.

**Trace.** Population, critère de sélection, taille, tableau ci-dessus, anomalies, conclusion, références des pièces.

**❓ Question.** *« Que contrôlez-vous sur une facture de vente ? »* **Réponse** : « Que la livraison ou la prestation est réelle et datée de la bonne période, que les calculs sont exacts, que le client est autorisé et que l'encaissement ou l'apurement est cohérent. »

---

## T4. Rapprochement facture / commande / réception / paiement

**Objectif.** Vérifier que **chaque facture payée** correspond à une commande autorisée et à une réception réelle (contrôle « à trois pièces » + paiement).

**Risque.** Paiement sans livraison, facture gonflée, doublon, achat non autorisé, dette oubliée.

**Documents.** Échantillon de factures fournisseurs ; bons de commande ; bons de réception ; relevés ou état de règlement.

**Étapes**
1. Sélectionner l'échantillon (voir T14).
2. Pour chaque facture, remplir la ligne : commande n° / réception n° / facture n° / paiement n°.
3. Comparer **désignation, quantité, prix** entre commande, réception et facture.
4. Vérifier le **bon à payer** (visa) et la **conformité du paiement** (bénéficiaire, montant, date).
5. Noter les écarts, rechercher l'explication (avenant, livraison partielle, remise).

**Exemple.**

| Facture | Quantité commandée | Quantité reçue | Quantité facturée | PU commande | PU facture | Écart |
|---|---:|---:|---:|---:|---:|---|
| FF-771 | 1 000 | 950 | 1 000 | 42,00 | 42,00 | **50 u. facturées non reçues = 2 100** |
| FF-780 | 200 | 200 | 200 | 118,00 | 124,00 | **Prix : 6 × 200 = 1 200** |

**Si une anomalie apparaît.** Demander au service achats la note de crédit ou l'explication ; si non justifiée, proposer une **correction de dette** (avoir à recevoir). Étendre l'échantillon si plusieurs écarts de même nature.

**Limites.** Une facture conforme aux pièces ne prouve pas l'**exhaustivité** des dettes (une facture absente n'est pas dans l'échantillon) → T5, T7, T9, T17.

**Trace.** Tableau 3-way, taille et méthode d'échantillon, écarts chiffrés, réponse du client.

**❓ Question.** *« Qu'est-ce qu'un rapprochement à trois pièces ? »* **Réponse** : « Comparer la commande, la réception et la facture sur la désignation, la quantité et le prix avant de payer. Il prévient les paiements sans livraison et les surfacturations. »

---

## T5. Circularisation (confirmation directe) des clients, fournisseurs, banques

**Objectif.** Obtenir d'un **tiers indépendant** une confirmation écrite **directement adressée à l'auditeur** (preuve de force élevée). 📘 BAO o.28, PDF p.148 ; 📗 DSCG p.456-460 ; 📙 SUPPORT p.11 (note 3)

**Risque.** Créance fictive (clients) ; dette omise (fournisseurs) ; engagements bancaires inconnus (banques) ; litiges non déclarés (avocats).

**Documents.** Balances auxiliaires à la date de clôture ; relevés de compte à envoyer ; modèle de lettre ; enveloppes pré-adressées **au cabinet** ; feuille de suivi.

**Étapes**
1. **Choisir** les tiers : soldes importants, **soldes anciens**, comptes annulés ou transférés, comptes au nom d'employés, soldes anormaux (ex. clients créditeurs). 📗 DSCG p.458-459. Banques, avocats, administrations : **exhaustif**.
2. Choisir le **type** : **fermée** (on indique le montant, ex. clients) ou **ouverte** (le tiers indique son solde, ex. fournisseurs, pour détecter les dettes omises). 📗 DSCG p.457-458 ; 📘 BAO o.28
3. Faire **préparer par l'entreprise** les lettres, relevés et enveloppes (signature du client) ; **vérifier** les adresses.
4. **Envoyer toi-même** (ou le cabinet) : le client ne poste pas ; les réponses reviennent **à l'adresse de l'auditeur**. 📗 DSCG p.460
5. **Enregistrer** les envois sur la feuille de suivi (date d'envoi, relances).
6. À réception : **pointer** chaque réponse (confirmé / écart / non-réponse).
7. **Analyser les écarts** (T5 b) ; conclure.

**Causes d'écart à rechercher** 📗 DSCG p.460 : chevauchements de factures (le client n'a pas enregistré les dernières factures) ou de règlements (la société n'a pas enregistré les derniers paiements) ; erreurs d'imputation ; **litiges**.

**Exemple chiffré.** Client Z : solde comptable **120 000**, réponse **100 000** → écart **20 000**.
- *Hypothèse A* : règlement de 20 000 émis le 29/12, encaissé le 05/01 → décalage de règlement, vérifié sur le relevé post-clôture → **pas d'anomalie**.
- *Hypothèse B* : facture de 20 000 du 30/12 pour un bien livré le 03/01 → **anomalie de cut-off** (T7).

**Positive vs négative** 📗 DSCG p.458 : *positive* = le client doit répondre ; *négative* = il ne répond que s'il est en désaccord (plus simple, mais une absence de réponse peut refléter de l'indifférence).

**Limites.** La confirmation prouve l'existence du solde à la date de réponse ; elle ne prouve ni la **recouvrabilité** ni l'**évaluation**.

**Trace.** Population, critère de sélection, liste des tiers, date d'envoi/relances, tableau de suivi (modèle 7.3), écarts expliqués, conclusion.

**Précaution.** 📘 BAO o.28 : jamais d'envoi par le client ; garder les preuves d'envoi ; anticiper les délais.

**❓ Question.** *« Comment circularisez-vous les fournisseurs ? »* **Réponse** : « En confirmation ouverte, sur une sélection basée sur les mouvements créditeurs les plus importants, envoyée par le cabinet avec retour direct. Je rapproche chaque réponse de la balance et j'explique les écarts. L'objectif est l'exhaustivité des dettes. »

---

## T6. Traitement des non-réponses à une circularisation

**Objectif.** Obtenir une preuve **équivalente** pour les tiers qui n'ont pas répondu. 📗 DSCG p.461 ; 📘 BAO o.28

**Risque.** Conclure sur la base d'un échantillon **non représentatif** parce que les non-répondants sont ceux qui posent problème.

**Documents.** Liste des non-répondants ; justificatifs d'envoi et de relance ; relevés bancaires post-clôture ; factures, bons de livraison ; liste des paiements post-clôture.

**Étapes**
1. **Relancer** (nombre et mode selon la méthodologie du cabinet 🧠) ; avec l'accord du client, contacter le tiers.
2. Si toujours rien : **procédures alternatives**.
3. **Clients** : examiner les **encaissements postérieurs** à la clôture (relevé bancaire) ; à défaut, rapprocher factures, bons de livraison et commandes. 📗 DSCG p.461
4. **Fournisseurs** : **cut-off** + **revue subséquente des décaissements** (T7, T9).
5. Évaluer si les éléments obtenus sont **suffisants** ; sinon, **procédures supplémentaires** et alerte au senior. 📗 DSCG p.461
6. Documenter le tout.

**Exemple chiffré.** 10 clients circularisés (1 200 000 de créances) : 6 réponses (680 000, aucune anomalie), 4 non-réponses (520 000). Alternative : **encaissements postérieurs** retrouvés pour 3 clients (390 000) ; pour le 4e (130 000), factures et bons de livraison signés obtenus. → **Couverture complète par procédures alternatives**.

**Si une anomalie apparaît.** Aucun encaissement ni bon de livraison signé : suspens à remonter ; ne pas conclure ; envisager dépréciation et nouvelles procédures.

**Limites.** Un encaissement postérieur prouve l'existence mais pas forcément que la créance concernait bien l'exercice ; vérifier le lien avec la facture.

**Trace.** Preuves d'envoi et de relance, procédure alternative choisie, pièces obtenues, conclusion par tiers.

**❓ Question.** *« Que faites-vous si un client ne répond pas à une circularisation ? »* **Réponse** : « Je relance, puis je passe aux procédures alternatives : je vérifie les encaissements après clôture sur le relevé bancaire et, à défaut, les factures, commandes et bons de livraison signés. Si les éléments sont insuffisants, je préviens le senior et j'étudie un risque de dépréciation. »

---

## T7. Test de cut-off autour de la clôture

**Objectif.** Vérifier que les opérations proches de la clôture sont comptabilisées **dans le bon exercice**. 📘 BAO o.27, PDF p.142

**Risque.** CA anticipé ou différé ; charges oubliées ; dettes non enregistrées (assertion **séparation des exercices**).

**Documents.** Journaux de ventes et d'achats des **deux mois avant et après** la clôture (usage 📘 BAO) ; bons de livraison et de réception ; contrats de prestations ; avoirs de janvier.

**Fait générateur** 📘 BAO : bien vendu → transfert de propriété (en général livraison) ; bien acheté → réception ; service → réalisation. **Ce n'est pas la date de facture.**

**Étapes**
1. Obtenir les journaux ; **sélectionner dès le début de la mission** les éléments pour avoir les pièces à temps.
2. Pour chaque élément, trouver la **pièce de date du fait générateur**.
3. Comparer l'**exercice de comptabilisation** à l'**exercice du fait générateur**.
4. Examiner **les avoirs de janvier** (ceux qui concernent N).
5. Vérifier les **régularisations** de fin d'exercice : FNP, FAE, CCA, PCA.
6. Quantifier l'effet sur le résultat et les soldes.

**Tableau de régularisation** 📘 BAO o.27

| Situation | Régularisation | Effet |
|---|---|---|
| Bien reçu / service rendu, facture non reçue | **FNP** (facture non parvenue) | Charge + dette |
| Facture comptabilisée, bien non reçu | **CCA** (charge constatée d'avance) | Charge réduite, actif |
| Client livré, non facturé | **FAE** (facture à établir) | Produit + créance |
| Client facturé, livraison non faite | **PCA** (produit constaté d'avance) | Produit réduit, passif |

**Cas pratique 2 — cut-off des ventes autour du 31 décembre** (société fictive).

| Facture | Date facture | Date BL | Exercice comptabilisé | Exercice correct | HT | Résultat |
|---|---|---|---|---|---:|---|
| V-2041 | 28/12/N | 28/12/N | N | N | 40 000 | ✔ |
| V-2049 | 30/12/N | **03/01/N+1** | N | **N+1** | **85 000** | **CA N surévalué** |
| V-2050 | 31/12/N | 31/12/N | N | N | 70 000 | ✔ |
| V-2051 | **02/01/N+1** | **30/12/N** | N+1 | **N** | **60 000** | **CA N sous-évalué** (FAE absente) |
| V-2052 | 03/01/N+1 | 03/01/N+1 | N+1 | N+1 | 25 000 | ✔ |

**Quantification** : CA N surévalué de 85 000 et sous-évalué de 60 000 → **effet net sur le CA de +25 000**, mais **chaque écart est une anomalie distincte** (ne pas les compenser dans le dossier). Pour V-2049, le **stock** de 31/12 doit aussi être corrigé (marchandise non encore livrée = en stock). Ajustements à **proposer** au senior (pas à comptabiliser) : annulation de la vente N, ajout d'une FAE pour V-2051, correction du stock au coût. La TVA : ❗ à traiter selon les règles d'exigibilité marocaines.

**Si une anomalie apparaît.** Étendre l'échantillon (ex. toute la dernière semaine) ; informer le senior ; vérifier si d'autres factures du même client ou de la même période sont concernées.

**Erreurs fréquentes.** 📘 BAO : confondre date de facture et de livraison ; ignorer les incoterms et les prestations à cheval sur deux exercices.

**Limites.** Le test ne couvre que l'échantillon ; il ne remplace pas le contrôle de la **complétude** des FNP et FAE.

**Trace.** Périmètre de dates, méthode de sélection, tableau ci-dessus, pièces, écarts, conclusion.

**❓ Question.** *« Comment réalisez-vous un test de cut-off ? »* **Réponse** : « Je prends les journaux de ventes et d'achats autour de la clôture, je sélectionne les écritures au-dessus du seuil, je récupère les bons de livraison ou de réception pour dater le fait générateur, et je vérifie que l'exercice comptabilisé est le bon. Chaque écart est soit une anomalie, soit déjà régularisé par FNP, FAE, CCA ou PCA. »

---

## T8. Rapprochement bancaire

**Objectif.** Vérifier que le **solde comptable de banque** est justifié par le **solde du relevé** et que les écarts (suspens) sont réels et apurés. 📘 BAO o.45, PDF p.233

**Risque.** Rapprochement falsifié ou erroné ; suspens anciens non justifiés ; opérations non comptabilisées ; fraude.

**Documents.** Rapprochement bancaire du client (chaque compte) ; relevé de clôture et relevés de janvier ; grand livre banque ; copies de chèques ; réponse de la banque (confirmation).

**Étapes**
1. Obtenir **tous** les rapprochements (aucun seuil de signification sur la trésorerie).
2. **Solde comptable** du rapprochement = grand livre / feuille maîtresse ; **solde bancaire** = relevé.
3. **Recalculer** (lignes et colonnes).
4. Examiner chaque suspens : **ancienneté**, **libellé**, **montant** (ronds, répétitifs), **pièce** (copie de chèque, avis), **apurement** sur le relevé de janvier.
5. Vérifier qu'il n'y a pas d'**opération en banque non comptabilisée**.
6. Comparer avec la **confirmation bancaire** (T5).
7. Vérifier l'absence de **virements internes non soldés** à la clôture.

**Cas pratique 4 — rapprochement bancaire** (compte 1, banque fictive).

| Ligne | Montant |
|---|---:|
| Solde du relevé au 31/12 | 912 500 |
| − Chèques émis non encore débités (n° 1041, 1042, 1045) | − 75 000 |
| + Remise déposée le 31/12 non encore créditée | + 10 000 |
| **Solde bancaire ajusté** | **847 500** |
| Solde comptable | 845 000 |
| **Écart** | **2 500** |

L'écart de **2 500** correspond à une **opération en banque non comptabilisée** (ex. virement client reçu). Actions : identifier la ligne sur le relevé, retrouver l'avis, proposer l'écriture (Débit Banque / Crédit Clients, 2 500), vérifier sur le relevé de janvier que les **3 chèques** et la **remise** ont été débités/crédités, et que l'**ancienneté** des chèques est normale.

**Si une anomalie apparaît.** Suspens ancien, libellé « divers », montant rond non justifié : alerte au senior ; ne conclus pas à la fraude.

**Limites.** Un rapprochement correct ne prouve pas que **toutes** les banques ont été listées : comparer à la liste des comptes (balance, confirmation).

**Trace.** Références des rapprochements, calculs, justificatifs de chaque suspens, apurement, conclusion.

**❓ Question.** *« Comment auditez-vous un rapprochement bancaire ? »* **Réponse** : « Je rapproche le solde comptable à la balance et le solde bancaire au relevé, je recalcule, puis j'examine chaque suspens : ancienneté, libellé, pièce, et surtout apurement sur le relevé de janvier. Je cherche aussi toute opération bancaire non comptabilisée et je compare à la confirmation de la banque. »

---

## T9. Revue subséquente des décaissements

**Objectif.** Détecter les **dettes de l'exercice non comptabilisées** en examinant les **paiements postérieurs à la clôture**. 📘 BAO o.29, PDF p.154

**Risque.** Dettes omises (exhaustivité) ; paiements injustifiés.

**Documents.** Relevés bancaires et journaux de banque des mois suivants ; justificatifs (factures, bons de réception, déclarations fiscales/sociales) ; liste des FNP comptabilisées.

**Quand l'utiliser** 📘 BAO : non-réponses à circularisation, activité à peu de mouvements, risque élevé, **intervention plusieurs semaines après la clôture**.

**Étapes**
1. Fixer la **période** (rarement plus de 3 mois) et le **seuil** (plus bas si le risque est élevé).
2. Lister **tous les décaissements** de la période au-dessus du seuil.
3. Pour chacun, obtenir le **justificatif** et déterminer l'**exercice de rattachement** (date du fait générateur, pas date de paiement).
4. Si rattaché à N : vérifier qu'il est **provisionné** (FNP ou dette).
5. Quantifier les omissions ; conclure.

**Cas pratique 3 — dette fournisseur non enregistrée** (seuil 30 000 ; décaissements de janvier N+1).

| Décaissement | Date | Montant | Justificatif | Rattachement | Provisionné ? |
|---|---|---:|---|---|---|
| Virement Transport Rif | 08/01 | **45 000** | Facture 28/12, prestation de décembre | **N** | **Non** → dette omise |
| Virement Papeterie Sebou | 12/01 | 60 000 | Facture janvier | N+1 | — |
| Virement assurance | 15/01 | 38 000 | Prime annuelle N+1 | N+1 | — |
| Virement Maghreb Pièces | 20/01 | 72 000 | Facture 20/12, réception 22/12 | **N** | Oui (FNP 72 000) ✔ |

**Conclusion** : **dette omise de 45 000** à proposer en FNP (charge N). Étendre le contrôle aux décaissements de décembre non encore comptabilisés. L'assurance de 38 000 est une charge N+1 (aucune action, sauf CCA de fin d'année si applicable).

**Si une anomalie apparaît.** Remonter le montant au senior ; vérifier s'il y a d'autres factures du même fournisseur ; pour un décaissement injustifiable, alerte immédiate.

**Limites.** Assurance **moindre** que la circularisation ouverte ; ne couvre que les dettes **payées** avant la date d'examen.

**Trace.** Période, seuil, liste complète des paiements, justificatif, rattachement, résultat.

**❓ Question.** *« Comment vérifiez-vous l'exhaustivité des dettes fournisseurs ? »* **Réponse** : « Par la circularisation ouverte des fournisseurs les plus mouvementés, le cut-off des achats autour de la clôture et la revue des paiements après clôture pour repérer toute facture de l'exercice non provisionnée. Je regarde aussi l'évolution des achats et du délai de paiement. »

---

## T10. Analyse de l'ancienneté des créances

**Objectif.** Apprécier la **recouvrabilité** des créances et la suffisance de la dépréciation. 📘 BAO o.43, PDF p.223

**Risque.** Créances anciennes non dépréciées ; clients en difficulté ; litiges.

**Documents.** **Balance âgée** (par échéance), balance générale, contrats, correspondance, encaissements post-clôture, informations sur les clients (situation financière).

**Étapes**
1. **Rapprocher** la balance âgée de la balance générale (T1).
2. Tester l'exactitude de l'**âge** : tirer des factures et recalculer l'échéance (date de facture + délai).
3. Lister les créances **au-dessus du seuil d'investigation** et **en retard**.
4. Pour chacune : demander l'**explication écrite**, vérifier les **encaissements post-clôture**, évaluer la solvabilité, lire l'**historique de correspondance**.
5. Comparer à la **dépréciation** comptabilisée ; discuter avec le senior de l'ajustement.

**Cas pratique 7 — créance à investiguer.** Seuil d'investigation 50 000. Client D : **100 000 HT** impayés depuis **150 jours**, pas de dépréciation. Le dirigeant : « il paiera, c'est un gros client ».
1. Aucun encaissement post-clôture. 2. Demander les échanges avec D et un **plan de paiement écrit**. 3. Examiner sa situation financière (information publique, litige, retards sur d'autres fournisseurs). 4. **Sans preuve de recouvrabilité**, proposer une **dépréciation** (jusqu'à 100 000 HT selon le risque) ; le montant exact est décidé par le senior. 5. Si D est un client majeur, signaler le lien avec la **continuité d'exploitation**.

**Conclusion à rédiger** : « Créance de 100 000 HT en retard de 150 jours, non dépréciée ; pas d'encaissement ni d'élément probant de recouvrabilité à la date de mes travaux ; je propose une dépréciation de X ; en attente de la décision du senior. »

**Limites.** L'âge d'une créance n'est qu'un **indice** ; une créance récente peut être irrécouvrable (client en faillite).

**Trace.** Rapprochement de la balance âgée, créances sélectionnées, explications (avec **source** : écrit ou oral), pièces, conclusion.

**❓ Question.** *« Comment auditez-vous les créances clients ? »* **Réponse** : « Je rapproche la balance auxiliaire de la balance générale, je circularise un échantillon, je teste le cut-off des ventes et j'analyse la balance âgée. Pour les retards significatifs, je cherche des encaissements postérieurs et des preuves de solvabilité avant de juger la dépréciation. »

---

## T11. Vérification des amortissements et dépréciations

**Objectif.** Vérifier que les dotations sont **recalculées correctement**, que la valeur nette est justifiée et que les indices de perte de valeur sont traités. 📘 BAO o.38 (PDF p.198), o.30 (PDF p.158) ; 📗 DSCG p.455-456

**Risque.** Durée ou mode d'amortissement inadaptés ; démarrage trop tard ou jamais ; dotation fausse ; absence de dépréciation d'actifs inutilisés ; manipulation du résultat (les amortissements et provisions sont des postes sensibles). 📙 SUPPORT p.37 (note 14)

**Documents.** Tableau de passage (valeurs brutes et amortissements) ; fichier des immobilisations avec dates de mise en service ; plan d'amortissement ; factures et procès-verbaux de mise en service ; politique comptable écrite.

**Étapes**
1. **Cohérence arithmétique** 📗 DSCG p.456 : *amortissements de clôture = amortissements d'ouverture + dotations − amortissements des immobilisations cédées ou hors d'usage*. Rapprocher les dotations au **compte de résultat**.
2. **Revoir la politique** : durée, mode (linéaire, dégressif), permanence N-1/N. Au Maroc, le mode **linéaire ou dégressif** est admis pour les corporelles et la **durée fiscale est fréquemment retenue** comme durée comptable 📙 SUPPORT p.14-15 (❗À vérifier dans le CGNC en vigueur).
3. **Recalculer** sur un échantillon (ou 100 % par tableur : T14, T16).
4. Contrôler le **point de départ** : date de **mise en service** (procès-verbal), pas la date de facture.
5. Contrôler les **cessions** : sortie du brut **et** des amortissements, plus ou moins-value, acquéreur (partie liée ?).
6. **Dépréciation** : indices de perte de valeur (actif inutilisé, obsolète, projet abandonné) ; analyse de la direction (valeur actuelle vs valeur nette).

**Cas pratique 5 — calculer et vérifier un amortissement.** Machine de **240 000** HT mise en service le **1er juillet N**, linéaire sur 8 ans.
- Dotation attendue = 240 000 ÷ 8 × 6/12 = **15 000**.
- Dotation comptabilisée : **30 000** → **surcharge de 15 000** (année pleine appliquée au lieu du prorata).
- Ajustement à proposer : Amortissements cumulés **Dr** 15 000 / Dotation aux amortissements **Cr** 15 000.
- **Étendre** le recalcul aux autres acquisitions de l'exercice (erreur de méthode probable) ; comparer 15 000 au seuil et au cumul des anomalies.

**Si une anomalie apparaît.** Calculer l'effet sur le résultat, informer le senior, vérifier si l'erreur est systématique.

**Limites.** Un recalcul exact ne dit rien sur la **pertinence** de la durée retenue ni sur la **valeur actuelle** de l'actif.

**Trace.** Politique, échantillon, recalcul (formule), écarts, conclusion.

**❓ Question.** *« Comment vérifiez-vous les amortissements ? »* **Réponse** : « Je rapproche le tableau de passage au bilan et au compte de résultat, je revois la durée et le mode, je recalcule sur un échantillon à partir de la date de mise en service, je contrôle les cessions et je regarde les indices de perte de valeur, notamment les actifs inutilisés. »

---

## T12. Observation et contrôle de l'inventaire physique

**Objectif.** Vérifier l'**existence** et la **quantité** des stocks (et autres actifs : caisse, effets, immobilisations). 📘 BAO o.26 (PDF p.138) et o.40 (PDF p.209) ; 📗 DSCG p.461-463

**Risque.** Quantités fausses ; double comptage ; articles non comptés ; **chevauchement** (articles reçus mais non enregistrés ou inversement) ; stocks chez des tiers ; articles abîmés.

**Documents.** **Instructions d'inventaire** ; listing valorisé des stocks (avant et après) ; fiches de comptage ; derniers **bons de réception et de livraison** ; procédure de gestion des stocks chez les tiers.

**Étapes**
1. **Avant** : lire les instructions, vérifier l'**arrêt des mouvements**, le comptage en double, le **comptage à l'aveugle**, la matérialisation des zones. 📘 BAO ; 📗 DSCG p.462
2. **Sur site** : accompagné d'un salarié connaissant les articles, observer le respect de la procédure ; faire des **tests de comptage dans les deux sens** :
   - du **listing vers le physique** (existence) : choisir les références aux **plus fortes valeurs** ;
   - du **physique vers le listing** (exhaustivité) : choisir des articles sur site et vérifier leur présence dans le listing.
3. Comparer tes comptages à ceux de l'entreprise ; en cas d'écart, **recomptage contradictoire** sur place.
4. Noter les **derniers numéros de bons de réception et de livraison** (N et N+1) pour le cut-off.
5. Noter les articles **abîmés, obsolètes, périmés** (indice de dépréciation).
6. **Après** : récupérer le **listing définitif** ; vérifier que les fiches de comptage sont correctement saisies et que les écarts constatés sont **corrigés** ; rester jusqu'à la fin. 📘 BAO ; 📗 DSCG p.462
7. Si ta présence est impossible, des **procédures alternatives** équivalentes sont nécessaires (décidées par le senior). 📗 DSCG p.463

**Cas pratique 6 — analyser une différence d'inventaire.** 15 références testées ; écart sur la référence **A12** : comptage entreprise **500**, ton comptage **480**, coût unitaire **85**.
1. **Recomptage contradictoire** : 480 confirmé.
2. Valeur de l'écart : 20 × 85 = **1 700** (anomalie **factuelle**).
3. Cause : erreur de saisie sur la fiche (500 au lieu de 480) ? double comptage ? mouvement non enregistré ? Obtenir la fiche et les mouvements intercalaires.
4. Si 3 références sur 15 présentent des écarts (**20 %** de l'échantillon), **ne conclus pas seul** : alerte au senior, qui décidera d'étendre les tests de comptage.
5. **Proposition** : correction du listing pour les écarts confirmés ; l'effet sur le résultat dépend du résultat de l'extension.

**Si une anomalie apparaît.** Écart non expliqué après recomptage : suspens, alerte immédiate. Stocks inaccessibles ou non comptés : le noter, le dire au senior.

**Limites.** L'observation physique confirme l'**existence**, **pas la valeur ni la propriété**. 📗 DSCG p.461 Elle ne détecte pas les articles chez des tiers.

**Trace.** Date, lieu, personnes présentes, instructions lues, nombre de tests, écarts, recomptage, listing définitif, derniers n° de bons.

**❓ Question.** *« Comment contrôlez-vous les stocks ? »* **Réponse** : « J'assiste à l'inventaire avec la procédure en main, je fais des tests de comptage dans les deux sens, je règle chaque écart par un recomptage contradictoire, je récupère le listing définitif et les derniers bons de réception et de livraison pour le cut-off, puis je teste la valorisation. »

---

## T13. Vérification de la valorisation des stocks

**Objectif.** Vérifier que les stocks sont évalués au **bon coût**, avec une méthode **constante**, et **dépréciés** si nécessaire. 📘 BAO o.41 (PDF p.213) et o.42 (PDF p.219)

**Risque.** Coût de revient erroné (coûts non incorporables, sous-activité non exclue) ; changement de méthode pour piloter le résultat ; obsolescence non dépréciée.

**Documents.** Listing valorisé ; dernières factures d'achat ; fichier du coût de production ; coûts standards ; fichier de dépréciation ; ventes récentes (prix de marché).

**Étapes**
1. **Comprendre la méthode** (CUMP, FIFO, coût standard) et sa **permanence**.
2. **Stocks achetés** : échantillon de références → **dernière facture d'achat** ; analyser l'évolution du coût unitaire N / N-1 par référence.
3. **Produits fabriqués / en cours** : vérifier que seuls les **coûts incorporables** sont inclus, que la **sous-activité** est exclue ; si coût standard, comparer standard / réel et la **mise à jour annuelle**.
4. **Dépréciation** : comprendre la méthode (ancienneté, rotation), vérifier la permanence, rapprocher le fichier de calcul à la balance, croiser avec l'inventaire (articles abîmés), puis tes propres analyses (rotation, ventes récentes).
5. Comparer **coût** et **prix de vente net** : si le prix est inférieur, dépréciation.

**Particularité marocaine** 📙 SUPPORT p.15 (comparaison IAS/IFRS vs normes marocaines) : en normes marocaines, les stocks sont enregistrés à la date du **transfert de propriété** ; la liste des coûts incorporables est plus restreinte qu'en IAS 2. ❗À vérifier dans le CGNC en vigueur.

**Exemples chiffrés**
- *Écart de coût* : référence X, dernière facture **40**, coût au listing **44**, 500 unités → surévaluation **(44 − 40) × 500 = 2 000**.
- *Dépréciation* : référence Y, 500 u. au coût **40**, prix de vente net attendu **30**, dépréciation comptabilisée **2 000** → nécessaire **500 × (40 − 30) = 5 000** ; insuffisance **3 000**. Ajustement à proposer : Dotation aux dépréciations des stocks **Dr** 3 000 / Dépréciation des stocks **Cr** 3 000.
- *CUMP vs FIFO* : achat 100 u. à 10, puis 100 u. à 12 ; vente de 120 u. FIFO : coût des ventes **1 240**, stock final 80 × 12 = **960** ; CUMP (11) : coût des ventes **1 320**, stock **880**. La méthode change le résultat de **80** : d'où l'exigence de permanence.

**Si une anomalie apparaît.** Calculer l'effet sur le résultat, vérifier si l'écart est systématique (même famille, même fournisseur), alerter le senior.

**Limites.** Il n'existe pas de « vérité » sur la dépréciation : on juge la **raisonnabilité** de l'estimation et la **stabilité** de la méthode.

**Trace.** Méthode, échantillon, factures consultées, écarts, analyse des dépréciations, conclusion.

**❓ Question.** *« Comment vérifiez-vous la valorisation des stocks ? »* **Réponse** : « Je comprends la méthode, je teste un échantillon de références avec la dernière facture d'achat, j'analyse l'évolution du coût unitaire, je vérifie les coûts incorporables pour les produits fabriqués et la permanence de la méthode, puis j'apprécie la dépréciation par la rotation, l'ancienneté et le prix de vente net. »

---

## T14. Sondage et sélection des éléments à contrôler

**Objectif.** Choisir **quoi** tester et **combien**, pour conclure sur une population sans la contrôler entièrement. 📘 BAO o.31 (PDF p.165) ; 📗 DSCG p.464-469

**Risque.** Échantillon **non représentatif** ; sélection biaisée ; conclusion abusive.

**Documents.** Population complète (listing rapproché de la comptabilité), critères de sélection, programme de test.

**Principe de base** 📘 BAO : **chaque élément doit pouvoir être sélectionné**. Les sondages **ne valident pas l'exhaustivité** d'une population (ils concernent surtout les **actifs**).

| Méthode | Principe | Usage |
|---|---|---|
| **Éléments spécifiques** (non statistique) | Tester **tous** les éléments au-dessus du seuil, ou à risque (valeur, ancienneté, nature) | Tests de substance ; pas d'extrapolation |
| **Échantillon standard** (non statistique) | Taille fixe selon la fréquence (25, 5, 2, 2, 1) | **Tests de contrôle** |
| **Statistique** (aléatoire, pas) | Taille calculée selon risque et erreur acceptable | Grande population non stratifiable ; extrapolation possible |
| **Sondage ordinaire (empirique)** | Choix libre de l'auditeur ; **varier** les programmes d'une année à l'autre pour créer un effet de surprise 📗 DSCG p.466 | Pratique courante ; vigilance sur la représentativité |

**Étapes**
1. Vérifier que la population est **complète** (rapprochée de la balance).
2. **Isoler** les éléments significatifs ou à risque : tests à 100 %.
3. Choisir la méthode pour le **reste** ; définir la taille selon le risque évalué et l'erreur tolérable (donnée par le senior).
4. **Sélectionner** (pas de choix sur ce qui est facile à tester) ; **garder la trace** de la méthode (aléatoire, pas, critères).
5. Réaliser les tests ; compter les erreurs ; **conclure** selon trois issues possibles : **accepter, continuer, refuser**. 📗 DSCG p.469

**Exemples chiffrés**
- *SUM (technique du pas)* 📘 BAO : stock 1 M€ en 3 000 lignes ; 15 lignes ≈ 330 K€ testées à part ; population restante ≈ 670 K€ ; erreur tolérable 20 K€ ; coefficient 1,2. Taille ≈ 670 000 × 1,2 ÷ 20 000 ≈ **40** ; **pas** = 670 000 ÷ 40 ≈ **16 667 €** ; première ligne tirée au sort, puis une ligne à chaque pas. (calcul de reconstitution cohérent avec le résultat du livre.)
- *Taille d'échantillon (loi normale)* 📗 DSCG p.466-467 : accepter 2 % d'erreurs dans une population, avec 1 % admis dans l'échantillon, confiance 95 % → **n = 380**.
- *Estimation d'un taux* 📗 DSCG p.468 : sur 200 factures d'achat, **20** sans bon à payer, soit **10 %** ; intervalle à 95 % : **5,84 % à 14,16 %**.

**Quand accepter** 📗 DSCG p.469 : échantillon représentatif ; erreurs peu nombreuses, **peu importantes**, **non systématiques**, **non intentionnelles** ; sinon refuser ou approfondir.

**Si une anomalie apparaît.** Erreur dans l'échantillon : appliquer la règle d'**extension** du programme (ex. 25 → 40 → 60 pour un contrôle journalier, BAO o.19) ; informer le senior.

**Limites.** Un échantillon **ne permet pas** de conclure sur l'**exhaustivité**. L'échantillonnage statistique suppose une population homogène et complète.

**Trace.** Population, rapprochement à la balance, éléments spécifiques, méthode, taille, résultats, conclusion.

**❓ Question.** *« Comment choisissez-vous vos échantillons ? »* **Réponse** : « Je teste d'abord à 100 % les éléments significatifs ou à risque, puis j'échantillonne le reste selon la taille donnée par mon senior, de façon aléatoire ou par pas, en traçant la méthode. Je ne conclus pas sur l'exhaustivité avec un sondage. »

---

## T15. Tests de contrôle et tests substantifs

**Objectif.** Savoir **lequel utiliser** et **ce qu'il prouve**. 📗 DSCG p.450-451 ; 📘 BAO o.19

| | **Test de contrôle (test de procédures)** | **Test substantif (contrôle de substance)** |
|---|---|---|
| **Cible** | Efficacité de la conception **et** du fonctionnement du contrôle interne | Détection d'anomalies **dans les montants** |
| **Deux types** | — | **Tests de détail** (opérations, soldes) et **procédures analytiques** |
| **Échantillon** | Standard (25, 5, 2, 2, 1) | Selon seuils et risques |
| **Si anomalie** | Contrôle déficient → risque de contrôle élevé | Ajustement comptable |
| **Preuve** | Le processus fonctionne (preuve **indirecte**) | Le solde est correct (preuve **directe**) |

**Approche mixte** 📗 DSCG p.450 : tests de procédures + tests substantifs ; dans certaines circonstances, **uniquement** des tests substantifs (si les contrôles sont absents ou non fiables).

**Choisir en pratique** 🧠 : fort volume de transactions standardisées → tests de contrôle utiles ; opérations rares ou estimations → tests substantifs ; poste à risque élevé → substantifs **toujours**.

**Exemple.** Achats : test de contrôle = « visa du bon à payer sur 25 factures » ; test substantif = « rapprocher 15 factures importantes aux commandes et réceptions et vérifier le cut-off ».

**❓ Question.** *« Différence entre un test de contrôle et un test substantif ? »* **Réponse** : « Le test de contrôle vérifie que le contrôle interne fonctionne, avec un échantillon standard, et son résultat est une conclusion sur le processus. Le test substantif vérifie directement les montants (par un test de détail ou une procédure analytique) et conduit à un ajustement chiffré si besoin. »

---

## T16. Procédures analytiques et investigation des variations

**Objectif.** Apprécier la **cohérence** des chiffres avec ce qu'on attend, et repérer les écarts à investiguer. 📗 DSCG p.453-455 ; 📘 BAO o.55 à 57 (PDF p.281-292)

**Risque.** Variation inexpliquée = anomalie non détectée ; **absence de variation** attendue = risque aussi.

**Quatre techniques (par ordre de complexité)** 📗 DSCG p.453-454 : **revue de vraisemblance** (composantes anormales : solde inhabituel, caisse créditeur, écritures sans libellé) ; **comparaison de données absolues** (N-1, budget, entreprises comparables) ; **comparaison de données relatives** (ratios d'exploitation, de structure, de rotation) ; **analyse de tendances**.

**Quand** : à la prise de connaissance, en **test de substance** (dans certains cas plus efficace que les tests de détail), et en **revue finale de cohérence**. 📗 DSCG p.454-455

**Étapes**
1. **Formuler l'attente avant de calculer** (activité, effectifs, prix, investissements). 📘 BAO
2. Calculer écart (en valeur et en %) et comparer au seuil d'investigation.
3. **Interroger** le responsable ; **évaluer le caractère adéquat** de la réponse (cohérente avec ce que tu sais ?).
4. **Corroborer** par un document ou une autre procédure (contrat, détail du compte, effectif).
5. Si pas d'explication satisfaisante : **autres procédures** (tests de détail). 📗 DSCG p.455
6. Conclure et référencer. Ne documente que les points **significatifs**.

**Cas pratique 9 — investiguer une hausse inhabituelle des charges.** Société fictive « Sebou Négoce ». Honoraires et frais de conseil : **N-1 = 1 200 000 → N = 2 220 000 (+85 %)** ; le CA est stable (+3 %). Seuil d'investigation 150 000.
1. **Attente** : hausse proche du CA (+3 %), soit environ **1 236 000**.
2. Écart inexpliqué ≈ **984 000**.
3. **Grand livre** : extraire les 10 écritures les plus importantes ; une écriture de **620 000** « honoraires projet » en décembre, une autre de 180 000 « conseil juridique ».
4. **Pièces** : contrat et facture du projet ; est-ce un **coût immobilisable** ou une charge ? réalité de la prestation ? période (T7) ? **partie liée** ?
5. **Explication du client** : projet de réorganisation, contrat signé en novembre ; **vérifier** (contrat, livrables, date).
6. Hypothèses (pas de conclusion à ce stade) : charge réelle exceptionnelle ; prestation partiellement rattachable à N+1 (CCA) ; classement erroné.
7. **Conclusion** : seulement après avoir vu contrat, livrables et période ; remonter au senior si l'un manque.

**Exemples de variations anormales à investiguer** 📙 SUPPORT p.36-37 : emprunts identiques N/N-1 (autre emprunt ? échéances impayées ? erreur ?) ; immobilisations absentes pour une société industrielle (sous-traitance ?) ; fournisseurs en forte baisse (risque d'arrêt d'activité) ; résultat N-1 ≠ réserves + report à nouveau (distribution de dividendes → PV d'AGO).

**Limites.** Les ratios n'ont de sens que si la **relation** entre les données reste stable ; mauvaise connaissance du secteur = fausses attentes. 📗 DSCG p.454

**Trace.** Attente, calcul, écart, explication (source), corroboration, conclusion.

**❓ Question.** *« Comment investiguez-vous une variation anormale ? »* **Réponse** : « Je fixe mon attente avant de regarder, je mesure l'écart, j'interroge le responsable, puis je vérifie l'explication par un document ou un autre indicateur. Si elle n'est pas satisfaisante, je fais des tests de détail. Je ne conclus que sur preuve et je remonte l'écart si je ne peux pas l'expliquer. »

---

## T17. Recherche de dettes non comptabilisées

**Objectif.** Vérifier l'**exhaustivité des passifs** (fournisseurs, dettes fiscales et sociales, provisions, engagements). 📘 BAO o.52 (PDF p.266), o.29

**Risque.** Dettes omises ou comptabilisées sur le mauvais exercice (le plus classique : résultat embelli).

**Documents.** Journaux d'achats et de banque de janvier et février ; balance auxiliaire fournisseurs ; relevés fournisseurs ; liste des FNP ; PV, correspondance, courriers d'avocats ; contrats récurrents (loyer, assurance, maintenance).

**Étapes (dans l'ordre d'efficacité)**
1. **Circularisation ouverte** des fournisseurs importants (T5), y compris ceux à solde faible mais très mouvementés.
2. **Cut-off achats** (T7) : réceptions de fin d'année facturées en janvier.
3. **Revue subséquente des décaissements** (T9).
4. **Dépouillement des factures reçues après clôture** : parcourir le journal d'achats de janvier-février pour repérer celles qui concernent N.
5. **Réceptions non facturées** : liste des bons de réception sans facture (FNP attendues).
6. **Relevés fournisseurs** : comparer aux dettes enregistrées.
7. **Contrats récurrents** : loyers, assurances, abonnements, maintenance : les charges à payer sont-elles là ?
8. **Dettes sociales et fiscales** : estimation analytique (primes, congés payés, impôts) puis comparaison (partie 5 F, G).
9. **Litiges et engagements** : PV, avocats, hors-bilan (T18).
10. Analytique : **délai moyen de paiement** et évolution des achats ; une baisse inexpliquée alerte. 📘 BAO o.52

**Exemple.** Journal d'achats de janvier : 3 factures de décembre pour **180 000** au total, FNP comptabilisées **110 000** → **70 000** d'omission potentielle à justifier.

**Si une anomalie apparaît.** Quantifier, proposer FNP, vérifier le **système de réception** (processus), étendre.

**Limites.** Aucune procédure seule ne garantit l'exhaustivité ; c'est la **convergence** des procédures qui rassure.

**Trace.** Procédures réalisées, sources, omissions chiffrées, conclusion.

**❓ Question.** *« Comment vérifiez-vous l'exhaustivité des dettes ? »* → voir T9. **Complément** : « Je n'oublie pas les dettes fiscales et sociales, les provisions et les engagements hors bilan. »

---

## T18. Vérification des provisions et des écritures de clôture

**Objectif.** Vérifier que les **provisions** sont **exhaustives** et **correctement évaluées**, et que les **écritures de clôture** sont justifiées. 📘 BAO o.49 (PDF p.254), o.50 ; o.47 (PDF p.244)

**Risque.** Litige ignoré ; provision sous-évaluée (ou excessive pour lisser le résultat) ; reprise sans objet ; régularisations oubliées.

**Documents.** Tableau de variation des provisions ; courriers d'avocats ; contrats et courriers de litige ; PV ; calculs de la direction ; liste des écritures de clôture.

**Étapes**
1. **Rapprocher** le tableau de variation : ouverture = N-1 audité ; dotations et reprises = compte de résultat.
2. **Exhaustivité** : circulariser les **avocats** ; entretien avec la direction et le service juridique ; lire PV et courriers de l'administration ; tenir compte des constats des autres travaux.
3. **Évaluation** : analyser chaque provision ; justifier chaque mouvement ; distinguer reprises **utilisées** (charge en contrepartie) et **non utilisées**.
4. **Écritures de clôture** : amortissements (T11), dépréciations (T10, T13), FNP/FAE/CCA/PCA (T7), écarts de conversion, provisions. Pour chaque OD significative : T2.
5. **Retraite et engagements du personnel** : vérifier les données de base, les hypothèses ; au besoin demander un **expert**. 📘 BAO o.50

**Particularités marocaines** 📙 SUPPORT p.16-17 (tableau IAS/IFRS vs normes marocaines) : actualisation des provisions **non obligatoire** ; **provision pour grosses réparations** admise ; **perte de change latente** inscrite en écart de conversion avec **provision pour risque de change** ; **gain latent** non intégré au résultat comptable ; **impôts différés** seulement dans les comptes consolidés ; avantages du personnel sans normalisation directe et précise. ❗À vérifier dans le CGNC en vigueur (support universitaire, date inconnue).

**Exemple.** Litige client : montant réclamé **600 000** ; réponse de l'avocat : risque « probable » estimé à **300 000** ; provision comptabilisée **100 000**. → Insuffisance **200 000** à proposer (décision du senior), avec la **lettre d'avocat** et l'analyse du risque en pièce jointe.

**Si une anomalie apparaît.** Quantifier et proposer ; le **jugement professionnel** sur l'estimation appartient au senior/CAC.

**Limites.** Il n'y a pas de montant « vrai » : on juge la **qualité de l'estimation** et sa **cohérence** avec les faits.

**Trace.** Tableau de variation rapproché, courriers d'avocats, analyse par provision, calcul, conclusion.

**❓ Question.** *« Comment vérifiez-vous qu'il n'y a pas de provision oubliée ? »* **Réponse** : « Par la circularisation des avocats, des entretiens avec la direction et le juridique, la lecture des PV et des courriers de l'administration, et en gardant en tête les litiges rencontrés pendant les autres travaux. »

---

## T19. Cohérence entre comptabilité et déclarations fiscales

**Objectif.** Vérifier que les montants déclarés (TVA, retenues, impôts, cotisations) sont **cohérents** avec la comptabilité. 📘 BAO o.54 (PDF p.274) et o.53 ; 📗 DSCG p.455-456 (rapprochements internes)

**Risque.** CA déclaré ≠ CA comptabilisé (redressement) ; TVA déduite à tort ; dettes fiscales mal estimées.

**Documents.** Déclarations de TVA de l'exercice (toutes) ; comptes de TVA ; comptes de produits ; états de paie ; déclarations de retenues et de cotisations ; calcul de l'impôt sur les sociétés.

**Étapes (TVA)**
1. Obtenir **toutes** les déclarations de l'exercice (mensuelles ou trimestrielles).
2. Lister les comptes de produits et distinguer **soumis / non soumis** (exports, exonérés).
3. **Confronter le total annuel des bases déclarées** au CA comptabilisé et expliquer les écarts. 📗 DSCG p.456
4. Recalculer la **TVA brute** = bases × taux et comparer au solde du compte de TVA collectée. 📗 DSCG p.456
5. Rapprocher la **TVA récupérable** aux charges et investissements ; la **TVA payée** au compte de TVA à décaisser.
6. Vérifier les **soldes du bilan** (dette ou crédit de TVA) à la dernière déclaration.

**Cas pratique 8 — rapprocher TVA et déclarations** (fictif ; TVA au taux normal de 20 %).

| Élément | Montant |
|---|---:|
| CA comptable annuel HT | 36 000 000 |
| − Ventes exonérées / export | − 4 000 000 |
| − Autres ventes à taux réduit (bases) | − 2 000 000 |
| = Base théorique au taux normal | 30 000 000 |
| **TVA théorique à 20 %** | **6 000 000** |
| TVA collectée comptabilisée (taux normal) | 5 940 000 |
| **Écart** | **60 000** |

**Investigation** : TVA collectée **sous-évaluée de 60 000** (bases ≈ 300 000 de CA) : décalages d'**exigibilité** (facture de décembre déclarée en janvier), avoirs, ventes exonérées mal séparées, erreur de taux. Demander le tableau annuel des déclarations, pointer mois par mois, quantifier le **risque fiscal** et transmettre au senior pour une éventuelle **provision**.

**Particularités marocaines (🇲🇦✔, sources secondaires, ❗À vérifier sur le site de la DGI)** : déclaration **mensuelle** pour les assujettis dont le CA de l'exercice précédent atteint ou dépasse **1 000 000 DH**, **trimestrielle** en dessous ; dépôt et paiement en général **avant le 20 du mois suivant** (ou du trimestre) ; télédéclaration **SIMPL-TVA**. **Taux : les sources divergent** (certaines indiquent que la réforme de la loi de finances 2024 a ramené le système à deux taux, 20 % et 10 %, au 1er janvier 2026 ; d'autres sites présentent encore quatre taux). **Ne cite pas de taux autre que le taux normal de 20 % sans contrôle dans le CGI.** Les règles d'exigibilité (encaissement ou débit) : ❗à vérifier.

⚠️ Le livre cite la **CA3** et la **TVA sur les débits** (France) : à ne pas transposer.

**Si une anomalie apparaît.** Quantifier le risque fiscal, ne **pas** conclure à une fraude, informer le senior.

**Limites.** Le rapprochement montre une incohérence, pas la **cause** : elle exige des pièces.

**Trace.** Tableau annuel déclarations / comptabilité, calcul de la TVA théorique, écarts, explications, conclusion.

**❓ Question.** *« Comment rapprochez-vous la TVA ? »* **Réponse** : « Je confronte les bases déclarées sur l'année au chiffre d'affaires comptable en séparant soumis et non soumis, je recalcule la TVA théorique et je la compare à la TVA collectée comptabilisée. Je justifie chaque écart : exigibilité, avoirs, exports, erreur de taux. Puis je rapproche les soldes de TVA du bilan avec la dernière déclaration. »

---

## T20. Documentation des anomalies et formulation des conclusions

**Objectif.** Que **n'importe quel relecteur** comprenne ce que tu as fait, trouvé et conclu. 📘 BAO o.10 (PDF p.62) et o.16 (PDF p.86)

**Structure de toute feuille** 📘 BAO o.10 : **objectif** (lié à l'assertion) → **travaux** (interlocuteurs, fichiers, étapes) → **résultats** → **conclusion**.

**Quatre conclusions possibles** : (a) **aucune anomalie**, objectif atteint ; (b) **anomalies** → ajustements ou reclassements proposés ; (c) **suspens** (pièce manquante) → impossibilité de conclure ; (d) **faiblesse** à suivre ou à recommander. **« Je ne peux pas conclure » est une conclusion** valable.

**Trois niveaux à distinguer**
| Niveau | Qui | Exemple |
|---|---|---|
| **Constat** | Toi | « 85 000 HT de ventes comptabilisées en N pour une livraison du 03/01/N+1 » |
| **Proposition d'écriture** | Toi, **après validation du senior** | « Annuler la vente N pour 85 000 » |
| **Décision d'ajustement et opinion** | Senior / manager / CAC | Corriger ou non, impact sur le rapport |

**Règle** 📘 BAO o.10 : une anomalie **ne reste jamais** au niveau de la feuille de travail ; elle est signalée au chef de mission et inscrite dans la **note de synthèse**. Garde la trace des **désaccords et obstacles**. 📕 ISO p.12

**Cas pratique 10 — feuille de travail rédigée avec anomalie** (voir le modèle vide en 7.1) :

| Rubrique | Contenu |
|---|---|
| **Référence** | D2.4 (ventes – cut-off) |
| **Objectif** | S'assurer que les ventes de fin d'exercice sont comptabilisées dans le bon exercice (assertion : séparation des exercices) |
| **Périmètre et population** | Journal de ventes du 01/11/N au 31/01/N+1, 312 factures, 4 820 000 HT |
| **Sélection** | 100 % des factures ≥ 40 000 HT (5 factures) + 5 factures au hasard (pas = 1/60) |
| **Pièces examinées** | Factures, bons de livraison signés (réf. D2.4-1 à 10) |
| **Travaux** | Comparaison date de facture / date du BL / exercice de comptabilisation ; vérification des FAE et PCA de clôture |
| **Résultats** | 8 éléments conformes ; **2 anomalies** : V-2049 (85 000, BL du 03/01/N+1, comptabilisée en N) et V-2051 (60 000, BL du 30/12/N, comptabilisée en N+1 sans FAE) |
| **Quantification** | CA N : **− 85 000** et **+ 60 000** ; créances N : −85 000 / +60 000 ; **stock N : + coût de V-2049** (à chiffrer) |
| **Conclusion** | Le test révèle **2 anomalies de séparation des exercices sur 10 éléments testés** (20 %) ; l'objectif **n'est pas atteint** pour les opérations de fin d'exercice. À étendre à toutes les factures de décembre et janvier. |
| **Faits observés / hypothèses** | **Fait** : 2 BL datés d'un exercice différent de la comptabilisation. **Hypothèse** : processus de facturation à la date de commande (à confirmer avec le service facturation) |
| **Proposition d'ajustement (à valider)** | Annuler V-2049 en N ; FAE de 60 000 pour V-2051 ; correction du stock ; TVA ❗à traiter selon exigibilité |
| **Suivi** | Alerté le [date] : senior [nom] ; décision en attente |
| **Revue** | Initiales et date du senior |

**❓ Question.** *« Que doit contenir une feuille de travail ? »* **Réponse** : « L'objectif lié à l'assertion, le périmètre et la méthode de sélection, les pièces examinées avec références, les travaux, les résultats chiffrés, les anomalies, la conclusion et les initiales de revue. Je distingue ce que j'ai observé de ce que je suppose. »

---

# PARTIE 5 — Les cycles comptables : guides pratiques détaillés

> **Mode d'emploi.** Chaque fiche liste ce que tu fais, dans l'ordre. Les techniques détaillées (T1 à T20) ne sont **pas répétées** : la fiche renvoie à elles. Réponse type à la question d'entretien *« Vous êtes junior et devez auditer ce poste : que faites-vous concrètement ? »* = les étapes numérotées de la fiche, dites avec tes mots.
>
> **Rappel des assertions principales** 📘 BAO o.17 : **actif** → existence + évaluation ; **passif** → exhaustivité + évaluation.

---

## A. Immobilisations (corporelles, incorporelles, financières)

📘 BAO o.38 (PDF p.198), o.23 (PDF p.127), o.30 (PDF p.158) ; 📗 DSCG p.463-464 (observation physique des immobilisations)

| Élément | Contenu |
|---|---|
| **Objectif** | Valeur brute existante et correctement évaluée ; amortissements exacts ; valeur nette justifiée ; propriété de l'entité |
| **Risques** | Acquisitions fictives ou non immobilisables ; **charges d'entretien qui auraient dû être immobilisées** ; mise en service tardive ; cessions mal comptabilisées ; actifs inutilisés non dépréciés ; production immobilisée gonflée |
| **Assertions** | Existence · Droits et obligations · Évaluation · Exhaustivité · Séparation des exercices |
| **Documents** | **Tableau de passage** (brut, amortissements) ; **registre / fichier des immobilisations** (n° d'inventaire, localisation, date de mise en service) ; factures ; **PV de mise en service** ; actes de cession ; titres de propriété ; contrats de leasing ; plan d'amortissement |

**Procédures dans l'ordre**
1. **Tableau de passage** : ouverture = N-1 audité ; clôture = balance (T1). Rapprocher les **totaux du registre** avec la comptabilité (T1). 📘 BAO o.23
2. **Acquisitions** (lignes au-dessus du seuil) : obtenir **facture** + **PV de mise en service** ; contrôler montant, **caractère immobilisable** (une dépense d'entretien n'est pas une immobilisation), **date d'entrée** et de mise en service, bénéficiaire de la propriété (T3).
3. **Frais accessoires** : transport, installation, droits : inclus au coût ; vérifier.
4. **Propriété** : acte, titre foncier ou carte grise ; contrat de crédit-bail (l'actif n'est pas à l'entité). ❗Procédure de vérification de la propriété foncière au Maroc à confirmer.
5. **Immobilisations en cours** : projet encore actif ? Mises en service transférées avec **démarrage de l'amortissement** ? 📘 BAO
6. **Production immobilisée** : rapprocher l'immobilisation et le **produit** ; contrôler les coûts capitalisés.
7. **Cessions** : sortie du **brut et des amortissements** ; plus ou moins-value → résultat **non courant** ; acheteur (partie liée ?) ; encaissement.
8. **Amortissements** : T11 (recalcul, durée, démarrage, dotation au CPC).
9. **Recherche d'immobilisations omises** : examiner les **comptes de charges** d'entretien, de petit matériel, de travaux au-dessus du seuil.
10. **Observation physique** 📗 DSCG p.463-464 : du **registre vers le bien** et du **bien vers le registre** (pour les biens meubles) ; applicable seulement si le contrôle interne des immobilisations est bon (nomenclature, fichier, inventaires physiques).
11. **Dépréciation** : indices (inutilisation, obsolescence, abandon) ; analyse de la direction (T11).
12. **Immobilisations financières** : titres, prêts, dépôts rapprochés de relevés et de confirmations ; comparer la **valeur nette des titres** aux **capitaux propres de la filiale** pour détecter une dépréciation. 📘 BAO o.30

**Particularités marocaines** 📙 SUPPORT p.14-15 (❗À vérifier dans le CGNC en vigueur) : **frais préliminaires** (frais d'établissement et à étaler) inscrits à l'actif et amortis sur **5 ans maximum** ; **R&D** : la recherche fondamentale en charge, la recherche appliquée pouvant être immobilisée, développement sous conditions, amortissement 5 ans maximum ; **réévaluation** admise mais **taxée** et rare ; **écart d'acquisition** inscrit à l'actif et amorti (durée maximale évoquée : 20 ans) ; **contrats de crédit-bail** : dans les comptes individuels, les loyers sont comptabilisés en charges d'exploitation. Ces points divergent d'IAS/IFRS : les distinguer dès que l'entité applique les IFRS (comptes consolidés).

**Anomalies recherchées** : facture ≠ montant comptabilisé ; immobilisation sans PV de mise en service ; amortissement qui n'a jamais démarré ; plus-value anormale sur cession à une partie liée ; immobilisation en cours ancienne ; titre dont la valeur nette dépasse largement les capitaux propres de la filiale.

**Exemple (cession)** : terrain cédé **250 000** pour une valeur nette de **100 000** → plus-value **150 000** au résultat non courant ; vérifier l'acquéreur, l'acte, l'encaissement et la décision sociale.

**Si anomalie** : règle générale (début partie 4) ; pour une dépense immobilisable passée en charge : proposer le reclassement et le **calcul de l'amortissement** associé.

**Trace** : tableau de passage rapproché, liste des acquisitions et cessions testées avec pièces, recalcul des amortissements, observation physique, conclusion.

**❓ Question** : *« Comment auditez-vous les immobilisations corporelles ? »* **Réponse** : « Je pars du tableau de passage rapproché des comptes audités. Je teste les acquisitions avec facture et mise en service, les cessions avec plus-value et encaissement, je cherche des dépenses immobilisables dans les charges, je recalcule les amortissements et je regarde les indices de perte de valeur, notamment les actifs inutilisés. »

---

## B. Stocks

📘 BAO o.40-42 (PDF p.209-222) ; 📗 DSCG p.461-463

| Élément | Contenu |
|---|---|
| **Objectif** | Quantités réelles, valorisation conforme et constante, dépréciation suffisante, cut-off correct |
| **Risques** | Quantités fausses ; double comptage ; coût erroné ; méthode changée ; obsolescence non dépréciée ; stocks chez les tiers ou de tiers chez l'entité ; cut-off |
| **Assertions** | Existence · Évaluation · Exhaustivité · Séparation des exercices · Droits et obligations |
| **Documents** | Instructions d'inventaire ; listing définitif valorisé ; fiches de comptage ; dernières factures d'achat ; fichier des coûts de production ; fichier de dépréciation ; derniers bons de réception et de livraison |

**Procédures dans l'ordre**
1. **Avant l'inventaire** : lire les instructions, préparer les tests (T12).
2. **Participation à l'inventaire** : tests de comptage dans les deux sens, recomptage contradictoire, récupération du listing définitif (T12).
3. **Rapprochement inventaire physique ↔ comptabilité** : le listing définitif (quantités × coût) doit être égal au solde du compte de stock (T1) ; le chevauchement est contrôlé ; en inventaire permanent, **contrôler les mouvements intercalaires** entre la date du comptage et la clôture. 📗 DSCG p.463
4. **Valorisation** : T13 (méthode, dernière facture, coût de production, sous-activité).
5. **Obsolescence et dépréciation** : analyse de rotation, ancienneté, ventes récentes, articles abîmés notés à l'inventaire (T13).
6. **Cut-off achats et ventes** : les derniers bons de **réception** (achats) et de **livraison** (ventes) de N et les premiers de N+1 sont rapprochés des journaux (T7).
7. **Stocks chez les tiers / de tiers** : obtenir la confirmation du tiers (T5 : stocks en dépôt). 📗 DSCG p.457
8. **Recherche et documentation des différences** : chaque écart est chiffré, expliqué, référencé.

**Anomalies recherchées** : écarts de comptage non réglés ; coût unitaire en forte hausse inexpliquée ; références sans mouvement depuis longtemps non dépréciées ; marge négative ; changement de méthode.

**Exemple chiffré** : voir T13 (écart de coût 2 000 ; dépréciation insuffisante 3 000 ; CUMP vs FIFO 80).

**Particularité marocaine** : stocks enregistrés au **transfert de propriété** et liste des coûts incorporables plus restreinte qu'en IAS 2. 📙 SUPPORT p.15 ❗À vérifier.

**Si anomalie** : voir T12-T13 ; une différence d'inventaire confirmée est une anomalie **factuelle** à chiffrer ; l'extension est décidée par le senior.

**Trace** : date et lieu de l'inventaire, nombre de tests, écarts, listing définitif, rapprochement au bilan, valorisation, dépréciation, cut-off.

**❓ Question** : *« Comment contrôlez-vous les stocks ? »* → réponse T12 + T13.

---

## C. Clients et chiffre d'affaires

📘 BAO o.43 (PDF p.223), o.21 (PDF p.114), o.27 ; 📙 SUPPORT p.15 (reconnaissance du CA)

| Élément | Contenu |
|---|---|
| **Objectif** | CA **réel**, complet, rattaché à la bonne période ; créances **existantes et recouvrables** |
| **Risques** | CA fictif ou anticipé ; avoirs et retours omis ; livraisons non facturées ; créances anciennes non dépréciées ; créances cédées (le risque d'impayé reste-t-il chez l'entité ?) |
| **Assertions** | Réalité · Exhaustivité · Mesure · Séparation des exercices · Existence · Évaluation · Droits et obligations |
| **Documents** | Journal de ventes ; balance auxiliaire ; balance âgée ; contrats, commandes ; bons de livraison ; factures et avoirs ; relevés bancaires ; réponses de circularisation ; contrat d'affacturage ou de cession |

**Procédures dans l'ordre**
1. **Comprendre la reconnaissance du CA** : fait générateur, ventes à l'avancement ou à l'achèvement, acomptes. 📘 BAO. **Marocain** 📙 SUPPORT p.15 : en normes marocaines, la **méthode à l'avancement est une option** (IFRS : obligatoire pour les prestations de service) ; CA selon la **forme juridique du contrat**. ❗À vérifier.
2. **Revue analytique** (T16) : évolution du CA par produit, client, mois ; marge ; délai moyen de règlement ; pic de fin de période.
3. **Test d'un échantillon de factures de vente** (T3, Cas 1) : de la **facture** → commande → livraison → encaissement (**réalité**) ; et de la **livraison** → facture (**exhaustivité**).
4. **Contrôle des pièces** : bon de commande signé, bon de livraison signé par le client, facture, preuve de transport.
5. **Circularisation clients** (T5) ; **non-réponses** (T6).
6. **Encaissements postérieurs** à la clôture (T6, T10).
7. **Ancienneté et dépréciation** (T10).
8. **Cut-off des ventes** (T7, Cas 2).
9. **Avoirs, retours, ristournes** : examiner les **avoirs de janvier** et les avoirs à établir ; un retour de marchandises de janvier concernant une vente de décembre est un indice de **reconnaissance anticipée**.
10. **Risque de fraude présumé sur les produits** 📘 BAO o.21 : écritures manuelles inhabituelles de fin de période, factures importantes sur les derniers jours, clients nouveaux ou parties liées.
11. **Créances mobilisées** (affacturage, cession) : lire le contrat, savoir **qui supporte l'impayé**, obtenir la liste des créances cédées. 📘 BAO o.43 (⚠️ « Dailly » est un dispositif français)

**Anomalies recherchées** : factures sans bon de livraison ; livraisons de janvier facturées en décembre ; hausse du CA concentrée sur la dernière semaine ; avoirs importants post-clôture ; écarts de circularisation inexpliqués ; créances > 90 jours sans dépréciation ni explication.

**Exemple** : voir T3 (Cas 1), T7 (Cas 2), T6, T10 (Cas 7).

**Si anomalie** : pour un risque de reconnaissance anticipée, **alerte rapide** au senior (poste sensible).

**Trace** : population, échantillon, tableau factures/pièces, circularisation (tableau), cut-off, balance âgée, conclusion.

**❓ Question** : *« Comment auditeriez-vous les créances clients ? »* → T10 ; *« …le chiffre d'affaires ? »* **Réponse** : « Je présume un risque de fraude sur les produits. Je comprends la reconnaissance du CA, je fais une revue analytique par produit et par mois, puis des tests de détail dans les deux sens (facture vers livraison pour la réalité, livraison vers facture pour l'exhaustivité), je teste le cut-off et les avoirs de janvier. »

---

## D. Achats et fournisseurs

📘 BAO o.52 (PDF p.266) ; 📗 DSCG p.538-543, 457-458

| Élément | Contenu |
|---|---|
| **Objectif** | **Exhaustivité** des dettes ; réalité des charges ; bonne période |
| **Risques** | Factures oubliées ou sur le mauvais exercice ; doublons ; paiement sans bon de réception ; factures fictives ; décalage pour embellir le résultat |
| **Assertions** | Exhaustivité · Séparation des exercices · Réalité · Évaluation · Classification |
| **Documents** | Balance auxiliaire fournisseurs ; commandes, bons de réception, factures ; relevés fournisseurs ; état de règlement ; liste des FNP ; journaux d'achats et de banque de janvier-février |

**Procédures dans l'ordre**
1. **Rapprocher** la balance auxiliaire fournisseurs de la balance générale (T1).
2. **Test à trois pièces + paiement** sur un échantillon (T4).
3. **Circularisation ouverte** des fournisseurs aux mouvements créditeurs les plus importants (T5) ; **non-réponses** (T6).
4. **Cut-off achats** (T7) : FNP et CCA.
5. **Revue subséquente des décaissements** (T9) et **recherche de dettes non comptabilisées** (T17).
6. **Revue analytique** (T16) : **délai moyen de paiement** (retards = difficultés ou litiges), ancienneté, évolution des achats. 📘 BAO o.52 ; 📙 SUPPORT p.37 (note 15 : une forte baisse des dettes fournisseurs peut signaler un arrêt d'activité).
7. **Fournisseurs débiteurs et comptes à solde anormal** : examiner tous les comptes fournisseurs débiteurs (indice d'avances, de double paiement ou de mauvais classement). 📗 DSCG p.455
8. **Contrôle du processus** (tests de contrôle, partie 3.10) : commande autorisée, réception, facture, bon à payer.

**Anomalies recherchées** : fournisseur important sans solde en fin d'année ; FNP absentes alors qu'il y a des réceptions ; factures de janvier relatives à décembre ; paiements sans pièce ; écarts de circularisation non expliqués.

**Réflexe de débutant à éviter** 📘 BAO : vérifier l'**apurement** de la dette (existence) alors que l'enjeu est l'**exhaustivité**.

**Exemples** : T4 (tableau 3-way), T9 (Cas 3, dette omise 45 000), T5.

**Trace** : balances rapprochées, échantillon avec pièces, tableau de circularisation, cut-off, revue subséquente, conclusion.

**❓ Question** : *« Comment vérifiez-vous l'exhaustivité des dettes fournisseurs ? »* → réponse T9.

---

## E. Trésorerie

📘 BAO o.45 (PDF p.233) ; 📗 DSCG p.457, 464-465

| Élément | Contenu |
|---|---|
| **Objectif** | Réalité et évaluation de la trésorerie ; réponse au risque de fraude |
| **Risques** | Rapprochement erroné ou falsifié ; suspens anciens ; comptes non déclarés ; engagements hors bilan inconnus ; virements de fin d'année « d'embellissement » |
| **Assertions** | Existence · Exhaustivité · Évaluation · Droits et obligations · Présentation |
| **Documents** | Rapprochements bancaires de **tous** les comptes ; relevés de clôture et de janvier ; confirmations bancaires ; journal de caisse ; relevés de portefeuille ; contrats (affacturage, escompte, cash-pool) |

**Procédures dans l'ordre**
1. Obtenir **tous** les rapprochements (aucun seuil de signification) ; comparer à la **liste des comptes bancaires de la balance** (T1).
2. **Rapprochement bancaire** : T8 (calculs, suspens, apurement, libellés).
3. **Contrôle des soldes** : solde du relevé = solde du rapprochement ; solde comptable = grand livre = feuille maîtresse.
4. **Confirmation bancaire** (T5) : soldes, effets escomptés non échus, lignes de crédit, cautions, nantissements, signataires autorisés ; rapprocher chaque réponse du dossier. 📗 DSCG p.458
5. **Vérification des opérations en suspens** : ancienneté, libellé, pièce, **apurement en janvier** (T8).
6. **Contrôle des virements proches de la clôture** 🧠 : lister les virements et remises des **derniers jours de décembre** et des **premiers jours de janvier** ; comparer la **date comptable** à la **date de valeur** sur le relevé ; repérer les virements internes (entre comptes de la même entité ou du groupe) **non soldés** à la clôture (risque d'un même fonds compté deux fois).
7. **Cohérence relevés / comptabilité** : la somme des mouvements du relevé de décembre doit correspondre aux écritures bancaires du mois (après suspens).
8. **Caisse** : comptage à la date de clôture ou en cours d'année avec procès-verbal, comparaison au journal de caisse, notification du résultat. 📗 DSCG p.464
9. **Valeurs mobilières de placement** : rapprocher des relevés de portefeuille, vérifier la dépréciation (moins-value latente).
10. **Flux** : rapprocher la trésorerie de clôture au **tableau de flux** s'il existe. 📘 BAO o.57

**Anomalies recherchées** : chèque émis très ancien non débité ; écritures sans pièce ; libellés incompréhensibles ; montants ronds répétés ; compte non répondu par la banque ; commissions inexpliquées.

**Exemple** : T8 (Cas 4, écart 2 500).

**Si anomalie** : un **suspens ancien non justifié** est un point à **risque élevé** : alerte immédiate (ne pas conclure à la fraude).

**Trace** : références des rapprochements, calculs, justificatifs de chaque suspens, apurement, confirmation, conclusion.

**❓ Question** : *« Comment auditez-vous la trésorerie ? »* **Réponse** : « Je rapproche chaque compte bancaire aux relevés et au grand livre, j'examine les suspens et leur apurement en janvier, je compare avec la confirmation de la banque, je regarde les virements proches de la clôture et je compte la caisse. »

