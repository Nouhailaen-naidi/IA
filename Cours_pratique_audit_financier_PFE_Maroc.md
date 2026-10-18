# Cours pratique d'audit financier — PFE Maroc

> Support opérationnel construit à partir de *La Boîte à outils de l'auditeur financier* (Dunod, 3e éd., 2022), adapté au contexte marocain.

## Mode d'emploi

**Légende des repères**
- 📘 = vient du livre
- 🧠 = notion générale ajoutée (hors livre)
- 🇲🇦 = complément marocain (statut de vérification en partie 13)
- ⚠️ = référence française à ne **pas** transposer automatiquement

**Choix de périmètre (à votre demande)** : le **Dossier 1 du livre** (normes NEP, déontologie, notes d'information CNCC, acceptation de mandat, blanchiment) est **volontairement ignoré**. Le cours démarre au Dossier 2. Seul un rappel minimal du cadre marocain figure en parties 1 et 13.

**Format par notion** : *Définition à retenir → Étapes → Exemple → Question d'entretien*. Les questions d'entretien sont placées **dans chaque notion** ; la partie 8 ne contient que des questions transversales (aucune répétition), et la partie 9 les mini-cas chiffrés.

**Ce qui n'a pas été lu** : voir partie 12 (pages sans texte exploitable dans le PDF, outils non analysés). Rien n'est présenté comme couvert s'il ne l'a pas été.

---

## Sommaire

1. Fondamentaux de la mission (version minimale)
2. Méthodologie, risques, assertions et seuils
3. Documentation et organisation des travaux
4. Techniques d'audit indispensables
5. Fiches pratiques par cycle comptable
6. Revue analytique et continuité d'exploitation
7. Définitions et distinctions à mémoriser
8. Questions d'entretien transversales
9. Mini-cas pratiques corrigés
10. Liste des notions à apprendre par cœur
11. Checklist finale de préparation
12. Sujets secondaires et limites de lecture
13. Sources et compléments marocains

---

# 1. Fondamentaux de la mission (version minimale)

**Définition à retenir** 🧠 : l'audit financier consiste, pour un auditeur indépendant, à obtenir une **assurance raisonnable (non absolue)** que les comptes ne contiennent pas d'**anomalies significatives**, afin d'exprimer une opinion sur leur régularité, leur sincérité et l'image fidèle.

**Déroulé standard d'une mission** 📘🧠 (à pouvoir réciter en 20 secondes) :

| Phase | Ce que fait l'auditeur |
|---|---|
| 1. Prise de connaissance et planification | Comprend l'entité et son environnement, fixe le seuil, identifie comptes et assertions significatifs, évalue les risques, rédige le plan de mission |
| 2. Réponse aux risques | Programme de travail par section : tests de contrôle, procédures analytiques, tests de détail |
| 3. Intervention finale | Cut-off, revue subséquente, circularisations, ajustements, lettre d'affirmation |
| 4. Conclusion | Note de synthèse, revue du dossier, opinion |

**Cadre marocain minimal** 🇲🇦 : l'audit légal est réservé aux **experts-comptables inscrits à l'Ordre (OEC)** ; les comptes sont établis selon le **CGNC** ; les normes d'audit de l'OEC sont alignées sur les **ISA**. Détails et statut de vérification en partie 13.

**❓ Question d'entretien** : *« Qu'est-ce qu'un audit financier, en une phrase ? »*
**✅ Réponse** : « C'est un examen indépendant des comptes qui permet à l'auditeur d'exprimer, avec une assurance raisonnable, une opinion sur le fait que les états financiers ne comportent pas d'anomalies significatives. Raisonnable, parce qu'on teste par sondage et selon des seuils, on ne revoit pas 100 % des opérations. »

---

# 2. Méthodologie, risques, assertions et seuils
*(Livre : Dossier 3, outils 17 à 22)*

## 2.1 Comptes et assertions significatifs (outil 17)

**Définition à retenir** 📘 : un compte est **significatif** quand il peut contenir une anomalie supérieure au seuil, par son montant (quantitatif) ou par sa nature : complexité, estimations, risque particulier (qualitatif). Une **assertion** est un critère dont dépend la régularité, la sincérité et l'image fidèle des comptes.

**Assertions (liste du livre, issue de la norme sur les éléments probants)** 📘

| Type d'information | Assertions |
|---|---|
| Flux d'opérations de la période (compte de résultat) | Réalité · Exhaustivité · Mesure · Séparation des exercices · Classification |
| Soldes de fin de période (bilan) | Existence · Droits et obligations · Exhaustivité · Évaluation et imputation |
| Présentation et annexe | Réalité/droits/obligations · Exhaustivité · Présentation et intelligibilité · Mesure et évaluation |

**Assertions principales en pratique** 📘 : comptes d'**actif** → **existence + évaluation** ; comptes de **passif** → **exhaustivité + évaluation**. (Un actif peut être surévalué, un passif oublié : c'est le sens du risque.)

**Étapes** 📘
1. Obtenir les derniers états financiers.
2. Comparer chaque compte au seuil de signification (par défaut, au-dessus = significatif).
3. Estimer les erreurs potentielles : complexité, volume, jugement/estimations.
4. Conclure et documenter : significatif ou non.
5. Déterminer les assertions principales de chaque compte significatif.

**Pièges** 📘 : subdiviser un compte si ses composantes n'ont pas le même risque (stocks de matières vs produits finis) ; un compte **sous le seuil** peut être significatif qualitativement (ex. provisions pour risques à solde nul alors qu'un litige existe) ; revisiter la liste chaque année.

**Exemple** : seuil 100 K. Compte « provisions pour litiges » = 0, mais litige en cours avec un concurrent → **compte qualifié de significatif**, assertion principale : exhaustivité.

**❓ Question** : *« Comment décidez-vous quels comptes auditer en priorité ? »*
**✅ Réponse** : « Je compare chaque compte au seuil, puis j'ajoute des critères qualitatifs : estimations, complexité, nature des flux, fraude potentielle. Pour chaque compte retenu, j'identifie les assertions principales : existence et évaluation à l'actif, exhaustivité et évaluation au passif. »

## 2.2 Risque inhérent (outil 18)

**Définition à retenir** 📘 : possibilité qu'une anomalie significative se produise **en l'absence de tout contrôle interne** ; évaluée selon la **probabilité** et l'**impact**. Classement du livre : faible / élevé / significatif.

**Étapes** 📘
1. Comprendre le secteur, la réglementation, l'activité, l'actionnariat, les flux intra-groupe, le rôle de l'informatique, les facteurs de fraude.
2. Sources : entretiens (direction, personnes clés), revue analytique préliminaire, procès-verbaux, organigrammes, rapports d'activité, manuel de procédures.
3. Évaluer probabilité × impact ; ne retenir que les risques réellement élevés (ne pas les multiplier).

**Exemple** 🧠 : société de négoce de métaux, cours très volatils → risque inhérent élevé sur la valorisation des stocks.

**❓ Question** : *« Différence entre risque inhérent et risque lié au contrôle ? »*
**✅ Réponse** : « Le risque inhérent existe avant tout contrôle, il vient de la nature de l'activité et du compte. Le risque lié au contrôle est le risque que le contrôle interne ne prévienne ou ne détecte pas l'erreur. »

## 2.3 Risque lié au contrôle et tests de contrôle (outil 19)

**Définition à retenir** 📘 : risque qu'une anomalie **échappe au contrôle interne** de l'entité. Évalué élevé / moyen / faible après tests de contrôle. **Sans contrôles, contrôles défaillants ou approche purement substantive → risque de contrôle élevé.**

**Étapes** 📘
1. Comprendre les systèmes comptables et informatiques.
2. Identifier, par processus et par compte significatif, les erreurs possibles et les contrôles en place.
3. Décider de tester ou non les contrôles (stratégie).
4. Sélectionner les contrôles clés et déterminer la taille d'échantillon.
5. Réaliser les tests, conclure : élevé / moyen / faible.

**Facteurs qui poussent à tester les contrôles** 📘 : fort volume de transactions, processus automatisé, complexité des systèmes, gain d'efficacité attendu. **À éviter** 📘 : conclure à l'efficacité d'un contrôle sur la seule base d'un test de cheminement.

**Échantillons minimaux, approche « complète »** 📘 *(taux à valider avec votre cabinet : repères du livre, d'origine française)*

| Fréquence du contrôle | Échantillon |
|---|---|
| Journalier | 25 |
| Hebdomadaire | 5 |
| Mensuel | 2 |
| Trimestriel | 2 |
| Annuel | 1 |
| Applicatif (automatique) | 1 (après validation des contrôles généraux informatiques) |

Approche « limitée » : échantillon réduit, conclusion « risque moyen » si tests satisfaisants.

**Si erreurs** 📘 : contrôle journalier → 1 erreur : échantillon étendu de 25 à 40 ; 2 erreurs : de 25 à 60 ; au-delà de 2 : contrôle déficient. Autres fréquences : **une erreur = contrôle déficient** → risque de contrôle élevé, mise à jour des procédures substantives, point pour la lettre de recommandation.

**Exemple** 📘 : processus achats, contrôle manuel journalier « rapprochement commande / bon de livraison / facture » ; échantillon 25 ; aucune anomalie → contrôle efficace, risque de contrôle réduit sur exhaustivité et évaluation des dettes.

**❓ Question** : *« Quelle est la différence entre un test de contrôle et un test de détail ? »*
**✅ Réponse** : « Le test de contrôle vérifie que le dispositif de contrôle interne fonctionne ; l'échantillon est standard et l'objectif est de comprendre l'origine des erreurs, pas leur impact financier. Le test de détail, ou contrôle de substance, vérifie directement des opérations ou des soldes, avec une sélection selon des seuils, et conduit à des ajustements chiffrés. »

## 2.4 Risque d'anomalies significatives, RAS (outil 20)

**Définition à retenir** 📘 : **RAS = combinaison du risque inhérent et du risque lié au contrôle**, par compte et par assertion. Il existe indépendamment de l'audit.

**Grille du livre** 📘

| | Risque de contrôle **élevé** | Risque de contrôle **moyen** | Risque de contrôle **faible** |
|---|---|---|---|
| **Risque inhérent élevé** | Maximum | Élevé | Moyen |
| **Risque inhérent faible** | Moyen | Faible | Minimum |

**Conséquence sur les travaux** 📘 : minimum → analytique + tests de détail très limités ; faible → analytique + tests de détail ; moyen → étendus ; élevé/maximum → très étendus. Plus le RAS est faible, plus on peut avancer les travaux avant la clôture.

**🧠 Modèle du risque d'audit** : Risque d'audit = RI × RC × RND. L'auditeur ne maîtrise pas RI et RC ; il **règle le risque de non-détection (RND)** par l'étendue de ses procédures.

**Exemple** : stocks avec valorisation complexe (RI élevé), pas de contrôle testé (RC élevé) → RAS maximum → tests de détail très étendus, inventaire physique + test de valorisation par échantillon important.

**❓ Question** : *« Comment passez-vous de l'évaluation des risques au programme de travail ? »*
**✅ Réponse** : « Je croise le risque inhérent et le risque de contrôle pour chaque compte et assertion. Plus le résultat est élevé, plus j'étends mes procédures : taille des échantillons, seuils d'investigation plus bas, travaux plus proches de la clôture. »

## 2.5 Risque de fraude (outil 21)

**Définition à retenir** 📘 : la fraude est un **acte intentionnel** (direction, employés ou tiers) impliquant une tromperie pour obtenir un avantage injuste. Deux formes : **détournement d'actifs** et **manipulation des états financiers**. Distinction avec l'erreur : l'intention.

**Étapes** 📘
1. Identifier les facteurs de risque : entretien avec la direction (appréciation du risque, procédures de prévention, éthique, fraudes avérées ou suspectées), entretien avec l'audit interne, procédures analytiques, constats pendant les travaux.
2. Évaluer probabilité et ampleur de l'impact.
3. Adapter l'approche : affectation des équipes, revue des choix comptables et des estimations, **test des écritures comptables**, introduire de l'**imprévisibilité**, comprendre la justification économique des opérations inhabituelles.
4. Concevoir des procédures de réponse : tests de contrôle, confirmations, entretiens, tests de détail, analyses spécifiques.

**À retenir** 📘 : **présomption de risque de fraude sur la comptabilisation des produits** ; si l'auditeur la juge inexistante, il doit le justifier dans le dossier. Garder l'esprit critique même si la direction a toujours été honnête.

**Exemple** 📘 : montants ronds ou répétitifs en rapprochement bancaire, libellés « divers », factures fictives qui apparaîtraient en rapprochement non justifié (révélées par circularisation fournisseurs).

**❓ Question** : *« Quel est votre rôle face à la fraude ? »*
**✅ Réponse** : « Je ne cherche pas la fraude systématiquement, mais je dois évaluer le risque, garder un scepticisme professionnel et adapter mes procédures : tests d'écritures inhabituelles, imprévisibilité, circularisation, revue subséquente des décaissements. Je présume un risque de fraude sur la reconnaissance des produits. Je ne peux donner qu'une assurance raisonnable, pas garantir l'absence de fraude. »

## 2.6 Seuil de signification (outil 22)

**Définition à retenir** 📘 : montant au-delà duquel une anomalie, seule ou cumulée, peut **influencer la décision d'un utilisateur** des états financiers. Il sert à (1) apprécier le caractère significatif des anomalies, (2) fixer les **seuils d'investigation** des tests. Sa détermination relève du **jugement professionnel**.

**Étapes** 📘
1. Choisir l'**agrégat** selon les attentes des utilisateurs et les caractéristiques de l'entité (secteur, résultat négatif, forte croissance, niveau de capitaux propres, endettement, résultat volatil, éléments exceptionnels).
2. Appliquer un taux dans la fourchette ; plus le risque d'audit est élevé, plus on retient un taux bas.

**Fourchettes de taux (indicatives, note CNCC XXI, juillet 2021)** 📘 ⚠️

| Agrégat | Taux |
|---|---|
| Résultat courant avant impôts | 3 à 10 % |
| Résultat net | 3 à 10 % |
| Chiffre d'affaires | 0,5 à 3 % |
| Charges | 0,5 à 3 % |
| EBITDA | 2 à 6 % |
| Endettement net (rarement appliqué) | 1 à 2 % |
| Holdings / fonds : total bilan | 0,5 à 3 % |
| Holdings / fonds : capitaux propres | 1 à 5 % (jusqu'à 10 %) |
| But non lucratif : revenus bruts ou charges | 0,5 à 2 % |

⚠️ Ces fourchettes sont **françaises** : à confronter au manuel OEC ou à la pratique de votre cabinet marocain ; à vérifier dans la réglementation et les normes marocaines en vigueur.

> **Limite de lecture** : les pages 120 à 125 du PDF fourni (suite de l'outil 22 : seuil de travail, seuils d'investigation, anomalies non corrigées) sont **vides** dans le fichier. Le lien entre seuil de signification et seuil de travail n'est donc pas repris du livre. Le livre mentionne seulement un « seuil de planification » (ex. : observer physiquement les machines au-dessus de 50 % de ce seuil).

**Exemple** : résultat courant avant impôts = 6 M MAD ; taux retenu 5 % → seuil = 300 000 MAD. Sous ce niveau, une anomalie isolée est en principe non significative, mais on la cumule avec les autres.

**❓ Question** : *« Comment fixez-vous le seuil de signification ? »*
**✅ Réponse** : « Je choisis l'agrégat le plus pertinent pour les utilisateurs, par exemple le résultat courant, et j'applique un taux dans une fourchette. Si le résultat est volatil ou négatif, je prends le chiffre d'affaires. Plus le risque est élevé, plus je prends un taux bas. Les anomalies s'apprécient aussi cumulées et qualitativement. »

---

# 3. Documentation et organisation des travaux
*(Livre : Dossier 2, outils 7 à 11, 13 et 16)*

## 3.1 Dossier permanent (DP) — outil 7

**Définition à retenir** 📘 : le DP est la **mémoire du dossier** sur toute la durée du mandat : informations stables sur l'entité et son environnement, contrats, éléments juridiques, analyses et rapports d'experts.

**Étapes** 📘
1. Le consulter dès qu'un élément d'un exercice passé est utile.
2. L'enrichir à chaque événement durable : acquisition de filiale, crédit-bail significatif, accord d'intéressement, contrat pluriannuel.
3. Garder la même structure pour tous les dossiers du cabinet ; privilégier le format électronique.

**Exemple** : copie des procès-verbaux d'assemblée justifiant les mouvements de capitaux propres (réutilisée chaque année).

**❓ Question** : *« À quoi sert le dossier permanent ? »*
**✅ Réponse** : « Il évite de redemander chaque année les mêmes documents et conserve la connaissance de l'entité : contrats, structure, PV, analyses passées. Il doit être mis à jour dès qu'un événement a un effet sur plusieurs exercices. »

## 3.2 Dossier de travail et référencement croisé — outil 8

**Définition à retenir** 📘 : le dossier de travail formalise la démarche et les travaux ; il doit permettre à un relecteur de comprendre l'approche et de **descendre au détail** (approche *top-down*) grâce au **référencement croisé**, qui matérialise la **piste d'audit**.

**Étapes** 📘
1. Suivre l'architecture du dossier de votre cabinet.
2. Référencer **toute** feuille (en haut à droite) ; une feuille non référencée ne fait pas partie du dossier.
3. Respecter le circuit feuille maîtresse → feuille de travail.

**Règle clé** 📘 : le référencement fonctionne **dans les deux sens** (descendant et remontant). Chaque chiffre renvoyé doit retrouver son pendant dans la feuille de destination. Test de qualité : ouvrir une page au hasard et remonter jusqu'à la feuille maîtresse.

**Exemple** 📘 : racine D2 = immobilisations → D2-1 → D2-1-1.

**❓ Question** : *« Comment un tiers retrouve-t-il votre travail ? »*
**✅ Réponse** : « Grâce au référencement croisé dans les deux sens : de la feuille maîtresse à la feuille de travail et inversement, avec les pièces justificatives classées derrière et référencées. »

## 3.3 Feuille maîtresse (lead schedule) — outil 9

**Définition à retenir** 📘 : détail par compte d'une section du bilan ou du compte de résultat (N et N-1), **point de départ des tests**, base de la revue analytique et du référencement croisé. Une feuille maîtresse par section ; la conclusion se trouve sur les feuilles de travail (ou en pied de feuille / mémo de section).

**Étapes** 📘
1. Créer les feuilles à partir de la balance générale N et N-1.
2. Vérifier que N-1 = comptes définitifs certifiés l'an dernier.
3. Affecter les feuilles aux collaborateurs ; suivre l'avancement via les références croisées.

**Contrôle de cohérence** 📘 : variation de stock au bilan = impact au compte de résultat ; mouvements de provisions au bilan = dotations/reprises en résultat.

**Revue par le chef de mission** 📘 : chaque compte doit avoir soit une référence/commentaire de travaux, soit être qualifié de **non significatif**.

**❓ Question** : *« Que vérifiez-vous en revoyant une feuille maîtresse ? »*
**✅ Réponse** : « Que tous les comptes de la section ont soit fait l'objet de travaux référencés, soit été jugés non significatifs au regard du seuil, et que la colonne N-1 correspond bien aux comptes certifiés. »

## 3.4 Feuille de travail — outil 10

**Définition à retenir** 📘 : document qui trace les travaux sur **un point précis**, compréhensible par un tiers, et qui **conclut**.

**Structure en 4 parties** 📘
1. **Objectif** lié aux assertions (ex. : réalité du stock).
2. **Travaux** décrits précisément (interlocuteurs, fichiers utilisés, étapes).
3. **Résultats** et conclusions intermédiaires.
4. **Conclusion** sur l'atteinte de l'objectif.

**Conclusions possibles** 📘 : (a) aucune anomalie, objectif atteint ; (b) ajustements ou reclassements ; (c) suspens (pièces manquantes) qui empêchent de conclure ; (d) faiblesses à suivre ou à recommander. **« Je ne peux pas conclure » est une conclusion à écrire explicitement.**

**À ne pas oublier** 📘 : une anomalie ne reste **jamais** au seul niveau de la feuille de travail ; la signaler au chef de mission et à la note de synthèse. Être synthétique.

**❓ Question** : *« Une pièce justificative manque : que faites-vous ? »*
**✅ Réponse** : « Je ne conclus pas sur cet élément. Je le note en suspens sur la feuille de travail, je relance le client avec une date, je cherche une procédure alternative (autre pièce externe, encaissement ou décaissement ultérieur) et, si rien n'aboutit, j'informe le chef de mission pour décider de l'impact sur la conclusion. »

## 3.5 Programme de travail — outil 11

**Définition à retenir** 📘 : outil à la fois de **structuration**, de **management** (répartition, suivi, supervision) et de **qualité** (cible les risques identifiés) ; défini **après** l'analyse des risques, par section.

**Étapes** 📘
1. Définir un programme adapté par section à partir des procédures standard.
2. Répartir entre collaborateurs.
3. Réaliser et documenter chaque travail avec référencement croisé.

**Points d'attention** 📘 : le superviseur fixe les **seuils d'investigation** ; le programme est mis à jour chaque année ; c'est un **guide, pas un carcan** : l'auditeur reste critique et l'adapte si les constats l'exigent.

**❓ Question** : *« Que faites-vous si le programme standard ne correspond pas à l'entreprise ? »*
**✅ Réponse** : « Je l'adapte à l'entreprise, par exemple selon sa méthode de valorisation des stocks ou son système d'information, j'en informe le superviseur et je documente la raison du changement. »

## 3.6 Supervision — outil 13

**Définition à retenir** 📘 : ensemble des diligences par lesquelles l'auditeur s'assure que les travaux délégués sont **suffisants et appropriés** pour fonder son opinion.

**Étapes** 📘 : évaluer la compétence des collaborateurs → répartir les tâches → suivre (adéquation compétences/tâches, compréhension des orientations, respect du programme) → traiter les problèmes complexes → adapter le programme → arbitrer les divergences → décider du recours à un expert → coaching → revue continue des travaux.

**❓ Question** : *« Comment votre travail est-il revu ? »*
**✅ Réponse** : « Par le chef de mission sur la conformité au programme, la qualité de la documentation, la résolution des points significatifs et le caractère suffisant des travaux. Les anomalies détectées remontent systématiquement. »

## 3.7 Plan de mission et note de synthèse — outil 16

**Définition à retenir** 📘 : le **plan de mission** (note d'orientation) présente l'approche ; la **note de synthèse** présente les conclusions.

| Plan de mission (avant) | Note de synthèse (pendant et après) |
|---|---|
| Calcul préliminaire des seuils | Seuil de signification définitif |
| Présentation de l'entité et de l'environnement | Points d'audit : risques, ajustements, reclassements |
| Risques inhérents, risque de contrôle, RAS par compte et assertion | Points en suspens |
| Risque de fraude | Rapprochement comptes audités / comptes définitifs |
| Programme de travail de l'intervention finale | Conclusion sur les comptes, revue analytique |

**Conseil** 📘 : alimenter la note de synthèse au fil de l'eau ; en fin de mission, vérifier qu'elle reflète la **dernière version des comptes** et qu'aucun suspens ne subsiste.

**❓ Question** : *« Quelle différence entre plan de mission et note de synthèse ? »*
**✅ Réponse** : « Le plan de mission dit ce que je vais faire et pourquoi, à partir des risques ; la note de synthèse dit ce que j'ai fait, ce que j'ai trouvé et ma conclusion. »

---

# 4. Techniques d'audit indispensables
*(Livre : Dossier 4, outils 23 à 35)*

## 4.0 Tests de détail vs procédures analytiques vs tests de contrôle 🧠📘

| | Test de contrôle | Test de détail (substantif) | Procédure analytique (substantive) |
|---|---|---|---|
| **Objet** | Fonctionnement du contrôle interne | Opération ou solde, pièce par pièce | Cohérence globale des chiffres et des variations |
| **Sélection** | Échantillon standard (ex. 25 pour un contrôle journalier) | Par seuil, stratification ou sondage | Aucune (tout le compte) |
| **Résultat** | Efficace / déficient | Anomalie chiffrée, ajustement | Écart inexpliqué à investiguer |
| **Cas d'usage** | Volume élevé, processus automatisé | Soldes significatifs, risque élevé | Charges/produits récurrents, revue globale |

**❓ Question** : *« Différence entre test de détail et procédure analytique ? »*
**✅ Réponse** : « Le test de détail vérifie des éléments individuels contre des pièces. La procédure analytique compare des chiffres avec mes attentes, issues de l'historique, du budget ou de la logique économique, et j'investigue les écarts. Elle ne remplace jamais les tests de détail sur les risques élevés. »

## 4.1 Tableau de passage — outil 23

**Définition à retenir** 📘 : tableau qui détaille ligne à ligne les **mouvements** entre le solde de clôture **N-1 audité** et le solde de clôture N, base des tests sur les postes à mouvements.

**Postes concernés** 📘 : immobilisations (incorporelles, corporelles, financières), amortissements, capitaux propres, provisions et dépréciations, consolidation.

**Étapes** 📘
1. Demander le tableau au client (souvent obligatoire dans les états de synthèse), ne pas le reconstruire soi-même.
2. Rapprocher soldes d'ouverture et de clôture avec les bilans audités N-1 et N.
3. Rapprocher certains mouvements au compte de résultat (amortissements, provisions).
4. Tester les mouvements (exhaustivité surtout pour les provisions) ; vérifier que le solde final répond aux assertions.

**Piège** 📘 : le tableau **n'est pas l'audit** ; il structure les tests. Si l'ouverture N-1 est fausse, la clôture le sera aussi.

**❓ Question** : *« Pourquoi partir de N-1 ? »*
**✅ Réponse** : « Parce que N-1 a déjà été audité : je concentre mes tests sur les mouvements de l'exercice, puis je conclus sur le solde de clôture. »

## 4.2 Rapprochement (bouclage) et vérifications arithmétiques — outils 24 et 25

**Définition à retenir** 📘 : le **rapprochement** vérifie que deux documents donnent le **même chiffre** (ou qu'un total est justifié par son détail) ; formalisé par référence croisée. La **vérification arithmétique** s'assure que les totaux et calculs d'un fichier sont exacts.

**Étapes** 📘
1. Sélectionner le chiffre à justifier.
2. Obtenir le document correspondant et en garder copie.
3. Formaliser le lien (référence croisée).
4. Pour les états de détail : conserver **la dernière page avec le total**, rapprochée du solde comptable.
5. Arithmétique : identifier les cellules calculées, recalculer à la main ou sous tableur, **vérifier lignes ET colonnes**, matérialiser par des symboles (ex. T pour total, @ pour formule).

**Limite** 📘 : un rapprochement n'est **pas** une validation. Si le détail et le compte viennent du **même logiciel comptable**, on a un bouclage, pas une preuve ; il faut ensuite remonter aux pièces externes.

**Exemple** 📘 : le total du listing des acquisitions d'immobilisations de l'exercice doit égaler la ligne « acquisitions » du tableau de passage.

**❓ Question** : *« Vous rapprochez la balance auxiliaire clients de la balance générale. Cela suffit-il pour conclure ? »*
**✅ Réponse** : « Non, c'est un bouclage entre deux états issus de la même source. Il permet d'utiliser la balance auxiliaire comme base de sélection pour la circularisation et le cut-off, mais la preuve d'audit vient des pièces externes. »

## 4.3 Validation des quantités physiques et inventaire — outils 26 et 40

**Définition à retenir** 📘 : le comptage physique est un moyen simple et fiable de vérifier l'**existence** d'un actif (stocks, immobilisations, caisse). Pour les stocks, l'entreprise doit compter chaque référence **au moins une fois par an**.

**Étapes (assistance à l'inventaire des stocks)** 📘
1. **Avant** : obtenir la procédure d'inventaire ; vérifier l'arrêt des mouvements, le double comptage ou le comptage à l'aveugle, les zones matérialisées.
2. **Sur site** : apprécier le respect de la procédure ; faire des **tests de comptage** à partir (a) du listing valorisé (plus fortes valeurs) et (b) de références choisies **physiquement sur site**.
3. Comparer ses comptages à ceux du client ; en cas d'écart, **recomptage contradictoire** le jour même.
4. **Récupérer le listing définitif** après inventaire (rester jusqu'à la fin).
5. Recueillir les **5 derniers bons de réception N et 5 premiers N+1** (cut-off) et noter les signes d'obsolescence (articles abîmés).

**Précautions** 📘 : toujours être accompagné d'un salarié connaissant les articles ; pour les stocks difficiles à compter (cuves, tas, petites pièces), comprendre la méthode (pesée de pièces par exemple).

**Exemple** : 15 références testées, 1 écart de 12 unités ; recomptage contradictoire → le client avait mal compté ; le listing définitif est corrigé.

**❓ Question** : *« Que faites-vous lors d'un inventaire physique ? »*
**✅ Réponse** : « Je lis la procédure en amont, puis sur site je vérifie qu'elle est respectée, je fais des tests de comptage dans les deux sens (du listing vers le physique et du physique vers le listing), je règle les écarts par un recomptage contradictoire, je récupère le listing définitif et les derniers bons de réception et de livraison pour le cut-off. »

## 4.4 Cut-off (séparation des exercices) — outil 27

**Définition à retenir** 📘 : tests qui vérifient que les opérations proches de la clôture sont enregistrées **sur le bon exercice**, en comparant la **date de comptabilisation** à celle du **fait générateur**.

**Fait générateur** 📘 : vente de bien → transfert de propriété (en général la livraison) ; achat de bien → réception ; service → réalisation du service. **Pas la date de facture**. Tenir compte des **incoterms** pour les flux lointains et du prorata pour les prestations à cheval sur deux exercices.

**Étapes** 📘
1. Obtenir les journaux d'achats et de ventes des mois avant et après clôture (en pratique **2 mois de chaque côté**).
2. Construire l'échantillon selon le seuil d'investigation (sélection dès le premier jour de mission pour avoir les pièces à temps).
3. Pour chaque ligne, obtenir le justificatif de la **date du fait générateur** (bon de réception, bon de livraison, attestation de service).
4. Vérifier que l'exercice du fait générateur = exercice de comptabilisation.

**Écritures de régularisation à connaître** 📘

| Cas | Régularisation |
|---|---|
| Bien reçu / service rendu, facture non reçue | **Facture non parvenue (FNP)** (charge + dette) |
| Facture enregistrée, bien non reçu / service non rendu | **Charge constatée d'avance (CCA)** |
| Client livré, non facturé | **Facture à établir (FAE)** (produit + créance) |
| Client facturé, bien non livré / service non rendu | **Produit constaté d'avance (PCA)** |

**Documents** : journaux d'achats/ventes, bons de réception, bons de livraison, contrats, factures. **Erreurs classiques** 📘 : confondre date de facture et date de livraison ; ignorer les incoterms. **Conclusion et limites** : le test couvre l'échantillon ; sans anomalie, la séparation est jugée correcte pour les flux testés ; il ne remplace pas le contrôle de la comptabilisation des FNP/FAE sur les opérations hors échantillon.

**Exemple** 📘 : chaque ligne testée doit présenter **deux croix dans la même colonne** (soit décembre, soit janvier : date de comptabilisation et date du fait générateur) ; sinon on investigue.

**❓ Question** : *« Comment testez-vous la séparation des exercices ? »*
**✅ Réponse** : « Je prends les journaux d'achats et de ventes de décembre, janvier et février, je sélectionne les écritures au-dessus du seuil, je récupère les bons de réception ou de livraison pour dater le fait générateur et je vérifie que l'exercice de comptabilisation est le bon. Chaque écart doit être expliqué : soit anomalie, soit déjà régularisé par FNP, FAE, CCA ou PCA. »

## 4.5 Circularisation (confirmation externe) — outil 28

**Définition à retenir** 📘 : demande de **confirmation par un tiers indépendant** d'une information ou d'un solde fourni par l'entité ; élément probant de **force très élevée**.

**Étapes** 📘
1. Sélectionner les tiers (critères adaptés à l'objectif).
2. Communiquer la liste à l'entreprise, qui prépare et **signe** les courriers.
3. **L'auditeur envoie lui-même** les courriers et la réponse revient **directement à lui** (jamais via le client).
4. Suivre les retours, relancer.
5. Exploiter les réponses : comparer à la comptabilité, expliquer chaque écart.
6. Pour chaque non-réponse : **procédure alternative**.

**Selon le tiers** 📘

| Tiers | Objectif | Sélection | Type |
|---|---|---|---|
| **Clients** | Existence et valorisation des créances | Balance auxiliaire à la clôture, sur le seuil | **Fermée** (on indique le montant) |
| **Fournisseurs** | **Exhaustivité** des dettes | Balance auxiliaire, **mouvements créditeurs cumulés** les plus significatifs | **Ouverte** (le fournisseur indique son montant) |
| **Banques** | Soldes, emprunts, cautions, nantissements, effets escomptés non échus | **Exhaustive** (tous les comptes bancaires de la balance) | — |
| **Avocats** | Exhaustivité des litiges et appréciation du risque | Extraction du compte honoraires + entretien avec la direction | — |
| Autres | Factor, administration, assurance, conseil en propriété intellectuelle | Au cas par cas | — |

**Procédures alternatives en cas de non-réponse** 📘
- **Clients** : vérifier l'**apurement** (encaissements postérieurs) ; si l'intervention est tardive, la circularisation est moins utile que l'étude de l'apurement ; en l'absence de preuve, bon de livraison.
- **Fournisseurs** : **cut-off** + **revue subséquente des décaissements** (assurance moindre que la circularisation).

**Traitement des écarts** 📘 : demander l'extrait de compte, rechercher la cause (facture comptabilisée chez le fournisseur et non reçue mais déjà provisionnée en FNP, règlement émis non reçu, litige, erreur) et conclure sur chaque écart.

**Précautions** 📘 : ne **jamais** laisser le client envoyer ; garder la copie des courriers (preuve de diligence, en l'absence de réponse) ; garder la liberté de choix des tiers ; anticiper les délais ; tirer parti des réponses bancaires (hors-bilan, intérêts, signataires).

**Exemple (livre)** 📘 : 5 fournisseurs sélectionnés, 4 réponses : 2 sans écart ; 1 solde supérieur (facture du fournisseur datée du 30 décembre, non reçue, mais **FNP déjà comptabilisée** → pas d'anomalie) ; 1 solde inférieur (règlement émis non reçu → rapprocher avec le relevé bancaire). Réponse manquante : test alternatif sur tous les paiements postérieurs, avec contrôle du cut-off et de la valorisation → exhaustivité de la dette conclue.

**Erreurs possibles** : n'envoyer qu'aux gros fournisseurs actuels (oublier un fournisseur à solde nul mais très mouvementé), laisser le client poster, ne pas conserver les preuves d'envoi. **Limite** : la confirmation prouve l'existence ou l'exhaustivité du solde confirmé à la date de réponse, pas la recouvrabilité d'une créance ni la valorisation d'un actif.

**❓ Question** : *« Que faites-vous si un client ne répond pas à la circularisation ? »*
**✅ Réponse** : « Je relance, puis je mets en œuvre des procédures alternatives : je vérifie les encaissements après clôture sur le relevé bancaire et j'obtiens les factures et les bons de livraison pour le solde non encaissé. Si l'apurement est incomplet, j'examine l'ancienneté et le risque de dépréciation. Je documente que les courriers ont bien été envoyés par mes soins. »

## 4.6 Revue subséquente des décaissements — outil 29

**Définition à retenir** 📘 : examen des **décaissements postérieurs à la clôture** pour identifier des dettes de l'exercice non comptabilisées (**exhaustivité des dettes**) et, accessoirement, des mouvements injustifiés (fraude).

**Quand l'utiliser** 📘 : après des travaux insatisfaisants (non-réponses à circularisation), quand l'activité génère peu de mouvements, en contexte de risque élevé. **Uniquement si l'intervention a lieu plusieurs semaines après la clôture.**

**Étapes** 📘
1. Choisir le nombre de mois (rarement plus de **3 mois** ; plus le risque est élevé, plus on étend).
2. Fixer le **seuil** (plus le risque est élevé, plus il est bas).
3. Sur les relevés bancaires des mois choisis, sélectionner **tous les décaissements** au-dessus du seuil.
4. Pour chacun, obtenir le justificatif (facture, bon de réception, déclaration fiscale ou sociale) et déterminer l'**exercice de rattachement** ; si c'est l'exercice audité, vérifier que le montant est **provisionné**.

**Conseils** 📘 : paiements par « campagne » → demander le détail et tester les principales lignes ; ne pas viser 90 % des mouvements ; virements internes entre comptes du groupe → constater la réciprocité seulement ; décaissement difficile à justifier → penser à la fraude.

**Exemple** : virement de 85 000 MAD en janvier N+1, facture de prestation de décembre N, aucune FNP comptabilisée → dette omise ; on propose un ajustement de 85 000 (hors taxes, à ajuster selon le régime de TVA).

**❓ Question** : *« Comment vérifiez-vous l'exhaustivité des dettes fournisseurs ? »*
**✅ Réponse** : « Je combine : la circularisation ouverte des fournisseurs les plus mouvementés, le cut-off sur les achats autour de la clôture, et la revue subséquente des paiements après clôture pour repérer toute facture se rapportant à l'exercice et non provisionnée. Je regarde aussi l'évolution des achats et le délai moyen de paiement. »

## 4.7 Sondage (échantillonnage) — outil 31

**Définition à retenir** 📘 : technique qui permet, à partir d'un **échantillon**, de conclure sur une population volumineuse. Principe : **chaque élément doit pouvoir être sélectionné**. Les sondages ne valident **pas l'exhaustivité** d'une population : ils s'appliquent surtout aux **actifs**.

| Méthode | Principe | Usage |
|---|---|---|
| **Non statistique, éléments spécifiques** | Découper la population selon des critères de risque et tester les catégories à risque (valeur > X, péremption, zone géographique) | **Tests substantifs** ; pas d'extrapolation |
| **Non statistique, échantillon standard** | Volume standard (ex. 25 opérations quotidiennes) | **Tests de contrôle** ; comprendre l'origine des erreurs |
| **Statistique (Random ou SUM/MUS)** | Taille calculée selon le risque et l'erreur acceptable ; extrapolation possible | Grande population sans stratification possible |

**Principes statistiques** 📘 : isoler et tester d'abord les éléments significatifs ; attendre peu d'erreurs ; toutes les lignes sélectionnables ; taille fonction du risque évalué et de l'erreur acceptable (tables). **Random** = tirage aléatoire ; **SUM** = technique du **pas** (population ÷ taille de l'échantillon), qui favorise les éléments les plus importants.

**Exemple (livre, SUM)** 📘 : stock de 1 M€ en 3 000 lignes ; 15 lignes spécifiques ≈ 330 K€ testées à part ; population restante ≈ 670 K€ ; erreur acceptable 20 000 € ; risque faible, aucune erreur attendue ; coefficient statistique 1,2.
- Taille ≈ 670 000 × 1,2 ÷ 20 000 ≈ **40** références (calcul de reconstitution, conforme au résultat du livre).
- **Pas** = 670 000 ÷ 40 ≈ **16 667 €** ; première ligne tirée au sort, puis une ligne tous les 16 667 € cumulés.

**À documenter** 📘 : raisons du sondage, méthode, hypothèses. Les méthodes statistiques peuvent forcer des extensions d'échantillon en cas d'anomalies.

**❓ Question** : *« Pourquoi échantillonner et comment ? »*
**✅ Réponse** : « Parce qu'on ne peut pas tout tester. Je teste d'abord les éléments significatifs ou à risque, puis j'échantillonne le reste. En non statistique, je ne peux pas extrapoler ; en statistique, je peux, mais je dois paramétrer le risque et l'erreur acceptable. L'échantillonnage ne couvre pas l'exhaustivité d'une population. »

## 4.8 Analyse de données — outil 32

**Définition à retenir** 📘 : exploitation informatique (tableur ou logiciels spécialisés) de fichiers volumineux pour tester **100 % d'une population** sans sondage et garder la trace des traitements.

**Étapes** 📘 : obtenir le fichier et le **rapprocher des comptes audités** → définir l'objectif (ex. créances de plus de 6 mois non dépréciées ; références de stock sans rotation depuis 12 mois ; OD mouvementant un compte de trésorerie) → choisir l'outil → appliquer et vérifier la cohérence → **mémo** détaillant chaque étape pour qu'un tiers retrouve le résultat → exploiter avec jugement.

**❓ Question** : *« Quel est l'intérêt de l'analyse de données ? »*
**✅ Réponse** : « Tester toute la population au lieu d'un échantillon : recalcul des amortissements, balance âgée, stocks dormants, écritures inhabituelles. Le traitement est mécanique, c'est l'interprétation des résultats qui relève du jugement. »

## 4.9 Tests de perte de valeur et dépréciations — outil 30

**Définition à retenir** 📘 : une **dépréciation** est constatée quand la valeur actuelle devient inférieure à la valeur nette comptable. L'auditeur **revoit l'analyse de la direction** (cohérence et exhaustivité) ; il ne se contente pas de l'insérer au dossier, il la « challenge ».

**Notions** 📘 : valeur actuelle (en normes françaises) = la plus élevée entre **valeur vénale** (prix de vente net) et **valeur d'usage** (flux futurs) ; en IFRS, la valeur recouvrable = la plus élevée entre juste valeur nette des coûts de sortie et valeur d'utilité.

**Étapes selon l'actif** 📘

| Actif | Démarche |
|---|---|
| Actifs avec référentiel objectif (placements, créances diverses) | Comparer la valeur comptable à la valeur de référence (ex. valorisation confirmée par la banque) |
| Créances clients, stocks | Approche spécifique (parties 5.2 et 5.3) |
| Immobilisations long terme | Valeur d'utilité = plan de trésorerie propre à l'actif, sur **5 ans maximum**, hypothèses documentées, flux actualisés comparés à la VNC ; attention aux actifs **non utilisés** (locaux vides, R&D non exploitée) : dépréciation immédiate possible |
| Titres de participation | Premier réflexe : comparer la VNC des titres aux **capitaux propres de la filiale** ; si inférieurs, demander valeur vénale (comparables) ou valeur d'usage (prévisions + plan de trésorerie) |

**Exemple (énoncé du livre ; la page de correction étant vide dans le PDF, la réponse ci-dessous est une reconstitution à partir des règles du livre)** : titres de B (VNC 50, capitaux propres de B 80, bénéficiaire) → pas de dépréciation ; titres de C (VNC 20, capitaux propres 10, créée en N-1, perspectives positives dès N+1) → analyser le business plan avant de décider ; fonds de commerce (acquis il y a 10 ans, VNC 50) dans une entreprise rentable → test formalisé ; **brevet** obsolète (VNC 10) → **dépréciation à envisager en totalité** (absence de flux futurs).

**❓ Question** : *« La direction ne fait aucun test de dépréciation sur une marque et des titres. Que faites-vous ? »*
**✅ Réponse** : « Je ne me contente pas d'explications orales : je mène ma propre analyse, par exemple comparer la valeur des titres aux capitaux propres de la filiale, demander un plan de trésorerie et en critiquer les hypothèses, et je propose un ajustement si la valeur d'usage est inférieure à la valeur comptable. »

## 4.10 Lettre d'affirmation — outil 35

**Définition à retenir** 📘 : lettre par laquelle la **direction confirme par écrit** ses déclarations à l'auditeur (obligation morale ; ne remplace pas les procédures).

**Contenu typique** 📘 : absence de fraude connue et procédures de lutte, respect des textes, absence d'événements remettant en cause la continuité, parties liées communiquées, cohérence entre hypothèses et intentions, absence d'événements post-clôture, position sur les **ajustements non corrigés**, autres confirmations.

**Étapes** 📘 : modèle adapté préparé par l'auditeur → exemplaire **signé** (dirigeant et directeur financier) vérifié → obtention avant le rapport.

**Alerte** 📘 : refus de signer = signal d'alarme (lettre « inversée » possible, conséquences sur l'opinion). La date de la lettre ne doit pas précéder celle du rapport de plus de quelques jours.

**❓ Question** : *« À quoi sert la lettre d'affirmation ? »*
**✅ Réponse** : « Elle formalise les déclarations de la direction, notamment sur la fraude, la continuité, les parties liées et les ajustements non comptabilisés. Elle ne remplace pas les preuves, mais un refus de la signer est un signal fort. »

---

# 5. Fiches pratiques par cycle comptable
*(Livre : Dossiers 5 et 6, outils 36 à 54)*

> **Question de référence pour chaque fiche** : *« Vous êtes auditeur junior et vous devez auditer ce poste : que faites-vous concrètement, étape par étape ? »* La ligne « Procédures » du tableau est la réponse, dans l'ordre.

## 5.1 Immobilisations (outils 36, 38, 39 ; R&D : outil 37 non détaillé)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Valeur brute existante et correctement évaluée (coût d'achat + frais accessoires) ; amortissements corrects ; valeur nette justifiée |
| **Risques principaux** | Acquisitions fictives ou non immobilisables ; **charges d'entretien qui auraient dû être immobilisées** ; durées d'amortissement incohérentes ; cessions mal comptabilisées ; absence de dépréciation d'actifs inutilisés ; production immobilisée qui capitalise des charges |
| **Assertions** | Existence · Droits et obligations (propriété) · Évaluation · Exhaustivité · Séparation des exercices (date de mise en service) |
| **Documents** | Tableau de passage valeurs brutes et amortissements ; listings à la clôture, des acquisitions, des cessions ; factures ; procès-verbaux de mise en service ; factures de cession ; titres, relevés de titres, contrats de prêts, dépôts et cautionnements |
| **Procédures** | 1. Obtenir le tableau de passage ; rapprocher ouverture/clôture avec les bilans audités N-1/N.<br>2. Rapprocher les totaux des listings avec le tableau.<br>3. **Acquisitions** : lignes > seuil → facture + PV de mise en service ; vérifier montant, caractère immobilisable, date d'entrée et de mise en service.<br>4. **Cessions** : rapprocher plus/moins-value du résultat non courant ; tester les principales ; identité de l'acquéreur (partie liée ?).<br>5. **Charges d'entretien/réparations** > seuil → rechercher une dépense immobilisable.<br>6. **Amortissements** : cohérence des durées ; rapprocher dotations et compte de résultat ; **recalculer** (échantillon ou 100 % par tableur).<br>7. **Immobilisations en cours** : projet toujours d'actualité ? Mises en service transférées et amortissement démarré ?<br>8. **Production immobilisée** : rapprocher l'immobilisation et le produit ; contrôler les coûts capitalisés.<br>9. **Valeur nette** : indicateurs de perte de valeur ; observation physique si besoin.<br>10. **Financières** : titres, prêts et dépôts rapprochés des justificatifs et relevés ; évaluation (derniers comptes, cours, flux actualisés) ; confirmation de tiers pour les montants significatifs |
| **Anomalies recherchées** | Facture ≠ montant comptabilisé ; immobilisation sans bon de mise en service ; amortissement qui démarre trop tard ou jamais ; plus-value anormale sur cession à une partie liée ; immobilisation en cours ancienne ; titre dont la VNC dépasse largement les capitaux propres de la filiale |
| **Conclusion** | Si les tests sur acquisitions, cessions et amortissements sont sans anomalie et qu'aucun indice de perte de valeur n'est relevé : valeurs brutes, amortissements et VNC présentés correctement. Les anomalies sont cumulées et comparées au seuil |

**Particularité 📘** : le tableau de passage est le **support**, pas la preuve ; les résultats des tests permettent l'opinion. Ne jamais valider l'existence en oubliant l'évaluation.

**Exemple 📘 (livre)** : terrain cédé 250 pour une VNC de 100 → plus-value de 150 à rapprocher du résultat non courant, acquéreur à identifier ; matériel brut 10 totalement amorti vendu 1 ; nouveau matériel acquis 15 ; bâtiment de 20 transféré des immobilisations en cours à « constructions » avec démarrage de l'amortissement.

**Complément chiffré 🧠** : dotation attendue = valeur brute ÷ durée × (mois d'utilisation ÷ 12). Machine de 240 000 mise en service le 1er juillet N, linéaire sur 8 ans : 240 000 ÷ 8 × 6/12 = **15 000**.

**❓ Question** : *« Comment auditez-vous les immobilisations corporelles ? »*
**✅ Réponse** : « Je pars du tableau de passage rapproché des bilans audités. Je teste les acquisitions au-dessus du seuil avec facture et mise en service, les cessions avec leur plus ou moins-value, je cherche des dépenses immobilisables dans les comptes d'entretien. Puis je recalcule les amortissements et je les rapproche du compte de résultat. Enfin, je regarde les indicateurs de perte de valeur, notamment les actifs inutilisés. »

## 5.2 Stocks (outils 40, 41, 42)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Quantités réelles (inventaire fiable), valorisation conforme et constante, dépréciation suffisante |
| **Risques principaux** | Quantités fausses ou double comptage ; stocks dans des lieux non comptés ; coût de revient erroné (frais commerciaux/financiers incorporés, sous-activité) ; **méthode changée pour piloter le résultat** ; stocks obsolètes sans dépréciation ; cut-off |
| **Assertions** | Existence (quantités) · Évaluation · Exhaustivité · Séparation des exercices · Droits et obligations (stocks chez des tiers) |
| **Documents** | Procédure d'inventaire ; listings valorisés (avant/après inventaire) ; dernières factures d'achat ; fichiers N et N-1 ; nomenclatures, coûts standards, fichier de dépréciation ; bons de réception/livraison |
| **Procédures** | 1. Lire la procédure d'inventaire, assister au comptage et faire les tests physiques (partie 4.3).<br>2. Récupérer le **listing définitif** et vérifier qu'il alimente le bilan.<br>3. **Stocks acquis** : identifier la méthode (**CUMP, FIFO**, LIFO pour sociétés étrangères) et les coûts accessoires ; échantillon de références → **dernière facture d'achat** ; analyse globale de l'évolution du coût unitaire N / N-1 par référence.<br>4. **Stocks transformés** : coût réel ou standard ; coûts incorporables (hors frais commerciaux et financiers) ; **sous-activité** exclue du coût ; encours : comprendre l'évaluation de l'avancement ; si coût standard, rapprocher standard/réel et vérifier la mise à jour annuelle.<br>5. Prix de vente moins marge théorique : cohérence du taux de marge avec la marge réelle et permanence.<br>6. **Dépréciation** : comprendre la méthode (ancienneté, rotation), vérifier la permanence, récupérer les fichiers de calcul, rapprocher avec la balance, croiser avec l'inventaire (articles abîmés), puis ses propres analyses (rotation, ancienneté, dernières ventes) ; discuter avec la direction |
| **Anomalies recherchées** | Écarts de comptage non réglés ; coût unitaire en forte hausse sans cause ; références sans mouvement depuis 12 mois et non dépréciées ; marge négative ; changement de méthode sans justification |
| **Conclusion** | Quantités validées par l'inventaire testé, valorisation justifiée sur l'échantillon et le contrôle de cohérence, dépréciation jugée suffisante ou ajustée. La « vérité » n'existe pas sur les dépréciations : on juge la **raisonnabilité** et la **stabilité** de la méthode |

**Repères 📘** : la part matière dépasse parfois 80 % du coût d'un produit fini → concentrer les travaux sur le coût matière. Une dépréciation purement mécanique peut être rejetée fiscalement ⚠️ (règle française ; **À vérifier dans la réglementation marocaine en vigueur**).

**Exemple chiffré 🧠 (CUMP vs FIFO)** : achat 100 u à 10, puis 100 u à 12 ; vente de 120 u.

| | FIFO | CUMP (moyenne 11) |
|---|---|---|
| Coût des ventes | 100×10 + 20×12 = **1 240** | 120×11 = **1 320** |
| Stock final (80 u) | 80×12 = **960** | 80×11 = **880** |

La méthode change le résultat de 80 : d'où l'exigence de **permanence**.

**❓ Question** : *« Comment vérifiez-vous la valorisation des stocks ? »*
**✅ Réponse** : « Je comprends d'abord la méthode : CUMP, FIFO, coût standard. Pour les stocks achetés, je teste un échantillon de références avec la dernière facture d'achat et j'analyse l'évolution du coût unitaire entre N-1 et N. Pour les produits fabriqués, je vérifie que seuls les coûts incorporables sont retenus, que la sous-activité est exclue et que le standard est à jour. Je vérifie aussi la constance de la méthode. »

## 5.3 Clients et créances (outil 43)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Créances **réelles**, rattachées au bon exercice et **recouvrables** |
| **Risques principaux** | Chiffre d'affaires fictif ou prématuré ; cut-off ; créances anciennes non dépréciées (« provisionner, c'est avouer ») ; créances mobilisées (affacturage, Dailly ⚠️) dont le risque reste chez l'entreprise ; avoirs non comptabilisés |
| **Assertions** | Existence · Évaluation · Séparation des exercices · Droits et obligations (créances cédées) · Classification |
| **Documents** | Balance auxiliaire clients ; balance générale ; **balance âgée** ; factures, bons de livraison, contrats ; réponses de circularisation ; relevés bancaires post-clôture ; contrat d'affacturage |
| **Procédures** | 1. Comprendre la **reconnaissance du CA** (fait générateur ; à l'avancement ou à l'achèvement ; acomptes déconnectés du CA).<br>2. **Revue analytique** : délai moyen de règlement vs délais légaux et pratiques ; évolution du CA et de la marge.<br>3. Rapprocher la balance auxiliaire de la balance générale.<br>4. **Circularisation** (fermée) sur la base de la balance auxiliaire.<br>5. **Cut-off** ventes.<br>6. **Balance âgée** : la rapprocher de la balance générale ; tester des échéances sur factures ; analyser les retards significatifs > seuil ; vérifier la dépréciation.<br>7. En cas de non-réponse ou d'absence de balance âgée : **revue d'apurement** (encaissements ultérieurs).<br>8. Si créances mobilisées : lire le contrat, savoir qui supporte l'impayé, obtenir la liste des créances cédées |
| **Anomalies recherchées** | Écarts de circularisation inexpliqués ; factures sans bon de livraison ; créances > 90 jours sans provision ni explication ; avoirs de janvier se rapportant à décembre ; clients à solde créditeur mal classés |
| **Conclusion** | Si rapprochements, circularisations (ou alternatives), cut-off et analyse de l'ancienneté sont satisfaisants : créances réelles et correctement évaluées. Si la dépréciation de la direction est trop faible : proposer un ajustement |

**Exemple 📘 (livre)** : seuil d'investigation 12 ; client C en retard de plus de 90 jours pour 30, le dirigeant explique un litige qualité et une dépréciation à 100 % ; l'auditeur **note les explications, vérifie que la provision est bien comptabilisée** et conclut que le retard a été pris en compte.

**❓ Question** : *« Comment auditez-vous les créances clients ? »*
**✅ Réponse** : « Je commence par la reconnaissance du chiffre d'affaires, puis la revue analytique du délai de règlement. Je rapproche la balance auxiliaire de la balance générale, je circularise un échantillon, je teste le cut-off ventes et j'analyse la balance âgée pour apprécier la dépréciation. En cas de non-réponse, je vérifie les encaissements après clôture. Je regarde aussi si des créances ont été cédées et qui supporte le risque d'impayé. »

## 5.4 Trésorerie et rapprochements bancaires (outil 45)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Réalité et valorisation de la trésorerie ; réponse aux risques de fraude |
| **Risques principaux** | Rapprochement bancaire falsifié ou erroné ; éléments en suspens anciens ; comptes non déclarés ; engagements hors bilan non connus ; moins-values latentes sur placements ; comptes de virements internes non soldés |
| **Assertions** | Existence · Exhaustivité · Évaluation · Droits et obligations · Présentation |
| **Documents** | Rapprochements bancaires de **tous** les comptes ; relevés bancaires (clôture et post-clôture) ; réponses de circularisation bancaire ; journal de caisse ; relevés de portefeuille (VMP) ; contrats (affacturage, escompte, cash-pool) |
| **Procédures** | 1. Obtenir **tous** les rapprochements (aucun seuil de signification sur la trésorerie).<br>2. Rapprocher le solde comptable à la feuille maîtresse ; le solde bancaire au relevé.<br>3. **Contrôle arithmétique** des lignes et colonnes.<br>4. Examiner les éléments en suspens : **ancienneté** (remonter à la facture et à la copie du chèque), **libellés anormaux** (« divers »), **montants ronds ou répétitifs** ; obtenir le détail et cadrer aux pièces.<br>5. Vérifier l'**apurement** sur les relevés post-clôture ; s'interroger sur toute opération en banque non comptabilisée.<br>6. **Circularisation bancaire** : rapprocher les réponses au dossier ; exploiter hors-bilan, intérêts, signataires.<br>7. VMP : rapprocher des relevés de portefeuille, tester la dépréciation (moins-value latente).<br>8. Caisse : journal de caisse, rapprochement, comptage.<br>9. S'assurer de l'absence de **virements internes** non soldés à la clôture.<br>10. Si cash-pool ou affacturage : comprendre les flux et le schéma comptable, réconcilier avec la société mère, obtenir les confirmations. Rapprocher les flux au **tableau de flux** |
| **Anomalies recherchées** | Chèques émis très anciens et non débités ; écritures sans pièce ; libellés incompréhensibles ; différences entre relevé et rapprochement ; absence de réponse bancaire pour un compte ; commissions ou intérêts inexpliqués |
| **Conclusion** | Rapprochement correct, suspens justifiés et apurés ; cohérence avec la confirmation bancaire. Un suspens ancien non justifié = point à fort risque (fraude possible) |

**Exemple 📘 (livre, rapprochement)** : le junior rapproche solde comptable et feuille maîtresse (J101), solde bancaire et relevé, vérifie les formules (tick marks), puis revoit les suspens : date d'apurement notée, écriture ancienne remontée à la facture et à la copie du chèque (J102), libellé « divers » justifié par le détail (J103).

**Exemple chiffré 🧠** : voir mini-cas 3 (partie 9).

**❓ Question** : *« Comment auditez-vous un rapprochement bancaire ? »*
**✅ Réponse** : « Je rapproche le solde comptable à la balance et le solde bancaire au relevé, je recalcule le tableau, puis je passe en revue chaque suspens : ancienneté, libellé, montant, pièce justificative, et surtout son apurement sur le relevé après clôture. Je vérifie enfin qu'il n'y a pas d'opération bancaire non comptabilisée et je compare avec la confirmation bancaire. »

## 5.5 Achats et fournisseurs (outil 52)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | **Exhaustivité** des dettes (objectif fondamentalement opposé à celui des clients : existence/exhaustivité) |
| **Risques principaux** | Factures oubliées ou comptabilisées sur le mauvais exercice ; double comptabilisation ; montant erroné ; factures fictives ; paiements sans bon à payer ; manipulation du résultat par décalage |
| **Assertions** | Exhaustivité · Séparation des exercices · Évaluation · Droits et obligations · Réalité des charges |
| **Documents** | Balance auxiliaire fournisseurs ; commandes, bons de réception, factures ; relevés fournisseurs ; réponses de circularisation ; relevés bancaires post-clôture ; liste des FNP |
| **Procédures** | 1. Rapprocher la balance auxiliaire de la balance générale.<br>2. **Circularisation ouverte** (mouvements créditeurs cumulés les plus significatifs).<br>3. **Cut-off achats**.<br>4. **Revue analytique** : délai moyen de paiement, ancienneté des dettes (retards = difficultés ou litiges), marge et charges externes (une anomalie peut révéler une double comptabilisation ou un oubli).<br>5. Si non-réponses : **revue subséquente des décaissements**.<br>6. Tests de contrôle du processus (commande → réception → facture → paiement) si stratégie de contrôle.<br>7. Recherche de fraude : factures fictives (circularisation), manipulation (cut-off), décaissements injustifiés |
| **Anomalies recherchées** | Fournisseur important sans solde en fin d'année ; FNP absentes alors qu'il y a des réceptions ; factures de janvier relatives à décembre ; paiements sans pièce ; écarts de circularisation non expliqués |
| **Conclusion** | Dettes jugées exhaustives si les procédures convergent. En présence de non-réponses, la conclusion repose sur des procédures alternatives, d'assurance moindre |

**Réflexe à éviter 📘** : le débutant vérifie l'apurement des dettes (existence) alors que l'enjeu est l'**exhaustivité**.

**❓ Question** : *« Comment vérifiez-vous l'exhaustivité des dettes fournisseurs ? »* → voir réponse 4.6.

## 5.6 Ventes et chiffre d'affaires 🧠 (cycle non présenté comme outil autonome dans le livre)

> Construit à partir des outils 21 (présomption de fraude sur les produits), 27 (cut-off), 28 (circularisation), 43 (clients) et 55-56 (analytique).

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | CA **réel**, complet, mesuré correctement et rattaché au bon exercice |
| **Risques principaux** | CA fictif ou anticipé (pression sur le résultat) ; livraisons non facturées ; prestations étalées mal reconnues ; avoirs omis ; ventes à des parties liées |
| **Assertions** | Réalité · Exhaustivité · Mesure · Séparation des exercices · Classification |
| **Documents** | Journal des ventes ; contrats ; commandes ; bons de livraison ; factures ; avoirs ; FAE ; PCA ; reporting commercial |
| **Procédures** | 1. Comprendre la politique de reconnaissance du CA et le fait générateur.<br>2. **Analytique** : évolution du CA par produit, client, mois ; marge brute ; rapport CA/créances ; pics de fin de période.<br>3. **Test de détail** : échantillon de factures du journal des ventes → commande, bon de livraison, facture, encaissement.<br>4. Test inverse (exhaustivité) : échantillon de bons de livraison → facture.<br>5. **Cut-off** ventes ; examen des avoirs de janvier.<br>6. Contrats pluriannuels : méthode à l'avancement ou à l'achèvement, calcul de l'avancement.<br>7. Vérifier les FAE et PCA de clôture.<br>8. Considérer le risque de fraude **présumé** sur les produits : écritures manuelles inhabituelles en fin de période |
| **Anomalies recherchées** | Factures sans livraison ; livraisons de janvier facturées en décembre ; hausse de CA concentrée sur la dernière semaine ; avoirs importants post-clôture ; clients nouveaux sans solvabilité |
| **Conclusion** | CA jugé réel et rattaché au bon exercice si tests de détail, cut-off et analytique convergent |

**❓ Question** : *« Comment auditez-vous le chiffre d'affaires ? »*
**✅ Réponse** : « Je présume un risque de fraude sur les produits. Je comprends la reconnaissance du CA, je fais une revue analytique par produit et par mois, puis des tests de détail dans les deux sens : de la facture à la livraison pour la réalité, de la livraison à la facture pour l'exhaustivité. Je teste le cut-off et les avoirs de janvier, et je recoupe avec les créances clients. »

## 5.7 Capitaux propres (outil 48)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Valider les capitaux propres ; toute variation doit s'expliquer par un **nombre limité d'opérations** |
| **Risques principaux** | Mouvement sans décision d'assemblée ; résultat affecté ≠ résultat audité ; dotation de réserve légale incorrecte ; ligne « autres » qui cache un mouvement injustifié |
| **Assertions** | Exhaustivité · Exactitude/évaluation · Droits et obligations · Présentation |
| **Documents** | Tableau de variation ; PV d'assemblées extraordinaires et ordinaires ; statuts ; registres ; états de synthèse N-1 audités |
| **Procédures** | 1. Obtenir le tableau de variation ; vérifier ouverture = N-1 audité, clôture = N.<br>2. **Opérations sur capital** → PV d'assemblée extraordinaire.<br>3. **Affectation du résultat et dividendes** → PV d'assemblée ordinaire.<br>4. Résultat reporté = résultat audité ; variation des provisions réglementées = dotations/reprises en résultat non courant.<br>5. Changements de méthode conformes aux règles.<br>6. Aucun mouvement sur une ligne de réserve en dehors des catégories ci-dessus (attention à « autres »).<br>7. Conserver les PV au dossier permanent |
| **Anomalies recherchées** | Dividendes versés sans décision ; mouvement de réserve sans cause ; écart entre résultat N-1 audité et résultat à affecter |
| **Conclusion** | Capitaux propres validés si chaque variation est justifiée par un PV ou par le résultat audité |

**Les seules causes de variation 📘** : opération sur capital, résultat de l'exercice (net des distributions), variation des provisions réglementées, changement de méthode comptable.

**Rappel ⚠️ 📘** : en France, réserve légale dotée de 5 % du résultat jusqu'à 10 % du capital (exemple du livre : dotation de 5 pour un résultat de 100). **À vérifier dans la réglementation marocaine en vigueur** avant de la citer en entretien.

**❓ Question** : *« Comment auditez-vous les capitaux propres ? »*
**✅ Réponse** : « Je pars du tableau de variation rapproché des bilans N-1 et N. Je justifie chaque mouvement par un procès-verbal : augmentation de capital en AGE, affectation du résultat et dividendes en AGO. Je vérifie que le résultat reporté est bien le résultat audité et qu'aucune ligne de réserve ne bouge sans cause. »

## 5.8 Provisions et dépréciations (outils 49, 50 ; 30, 42, 43)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Variation justifiée ; **exhaustivité** et **évaluation** (meilleure estimation de la direction) |
| **Risques principaux** | Litige ignoré ; provision sous-évaluée ou « cookie jar » ; reprise sans objet utilisée à tort ; engagements de retraite incomplets ; hypothèses non documentées |
| **Assertions** | Exhaustivité · Évaluation · Présentation (annexe) · Classification (reprises utilisées / non utilisées) |
| **Documents** | Tableau de variation des provisions ; courriers d'avocats ; contrats, courriers de litige ; contrôles fiscaux ; calculs actuariels ; rapport d'expert |
| **Procédures** | 1. Obtenir le tableau de variation ; rapprocher ouverture/clôture et dotations/reprises avec le compte de résultat.<br>2. **Exhaustivité** : circularisation des **avocats** (sélection selon honoraires), entretiens avec la direction, lecture des PV et courriers, constats des autres travaux.<br>3. **Évaluation** : analyser chaque provision, justificatif de chaque mouvement ; distinguer reprises **utilisées** (charge en contrepartie) et **non utilisées** (provision sans objet).<br>4. Si hypothèses hors compétence : demander un expert ; hypothèses en annexe et dans la lettre d'affirmation.<br>5. **Retraite** : comprendre les engagements, identifier convention collective ou accord (montant le plus favorable), vérifier les **données de base** (dates, salaires), revoir les **hypothèses actuarielles** (table de mortalité, taux d'actualisation selon la duration, augmentation des salaires, rotation), recalculer ou s'appuyer sur le rapport de l'expert |
| **Anomalies recherchées** | Réponse d'avocat mentionnant un litige non provisionné ; reprises sans événement ; hypothèses incohérentes avec l'historique ; données de base fausses |
| **Conclusion** | La validation repose sur le **jugement professionnel** : accepter l'estimation de la direction si elle est étayée, ou proposer un ajustement. Reconnaître quand une expertise est nécessaire |

**Définition à retenir 📘** : une provision est un passif dont l'échéance ou le montant n'est pas précisément fixé, correspondant à une obligation envers un tiers dont il est probable ou certain qu'elle entraînera une sortie de ressources sans contrepartie équivalente (référence française, proche de l'IAS 37).

**❓ Question** : *« Comment vérifiez-vous qu'il n'y a pas de provision oubliée ? »*
**✅ Réponse** : « Par la circularisation des avocats, des entretiens avec la direction et le service juridique, la lecture des procès-verbaux et des courriers de l'administration, et en gardant en tête les litiges rencontrés pendant les autres travaux, notamment le cut-off et la revue subséquente. »

## 5.9 Emprunts et dettes financières (outil 51)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Exhaustivité et exactitude des dettes financières ; information en annexe |
| **Risques principaux** | Emprunt non comptabilisé ; intérêts courus omis ; **covenants non respectés** ; engagements hors bilan non mentionnés ; comptes courants non confirmés |
| **Assertions** | Exhaustivité · Évaluation · Présentation · Droits et obligations |
| **Documents** | Contrats d'emprunt, tableaux d'amortissement ; réponses de circularisation bancaire ; conventions de compte courant ; contrats d'émission obligataire |
| **Procédures** | 1. Décomposer : emprunts, intérêts courus non échus, comptes courants.<br>2. Rapprocher dettes et mouvements des **échéanciers** et de la **confirmation bancaire**.<br>3. Emprunt obligataire : terme, remboursement, prime de non-conversion, annexe.<br>4. **Intérêts courus non échus** provisionnés si l'échéance n'est pas à la clôture.<br>5. **Comptes courants** : confirmation intragroupe et nature des flux.<br>6. **Hors bilan** : covenants, cautions, nantissements ; vérifier le **respect** des covenants à la clôture.<br>7. Cohérence entre charges d'intérêts et dettes.<br>8. Capacité à faire face aux échéances → lien avec la continuité d'exploitation |
| **Anomalies recherchées** | Écart avec la banque ; charge d'intérêts trop faible par rapport à la dette ; covenant dépassé non signalé ; compte courant mal classé |
| **Conclusion** | Dettes exhaustives et conformes aux contrats ; si covenant rompu, conséquences sur le classement (court terme) et sur la continuité |

**❓ Question** : *« Que vérifiez-vous sur les emprunts ? »*
**✅ Réponse** : « Je rapproche le capital restant dû et les échéances avec le tableau d'amortissement et la confirmation de la banque, je contrôle les intérêts courus, je lis les clauses du contrat pour les covenants et les garanties et je vérifie qu'ils sont respectés à la clôture et mentionnés en annexe. »

## 5.10 Dettes fiscales et sociales, hors TVA (outil 53)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Exhaustivité et évaluation des dettes fiscales et sociales à la clôture |
| **Risques principaux** | Charges de personnel ou impôts sous-estimés ; primes et congés non provisionnés ; contrôles en cours non provisionnés ; calcul de l'impôt erroné |
| **Assertions** | Exhaustivité · Évaluation · Séparation des exercices |
| **Documents** | Déclarations fiscales et sociales ; états de paie ; bordereaux ; calcul de l'impôt sur les sociétés ; correspondances avec l'administration ; litiges prud'homaux |
| **Procédures** | 1. **Revue analytique** : taux de charges apparent, salaire moyen, charges de personnel vs effectifs, hausses et primes (**définir ses attentes avant de comparer**).<br>2. Rapprocher dettes et déclarations ; **test de cohérence** (taux théorique × assiette).<br>3. Revue critique du calcul de l'impôt sur les sociétés et des taxes.<br>4. Rapprocher les états financiers des déclarations sociales.<br>5. Suivre les contrôles en cours ou terminés.<br>6. **Cut-off** + revue subséquente des décaissements (débouclage des dettes estimées : primes).<br>7. Au besoin : circularisation des organismes sociaux ; revue des litiges prud'homaux |
| **Anomalies recherchées** | Taux de charges sociales apparent incohérent ; dette sociale ≠ déclaration ; absence de provision pour congés ou primes ; contrôle fiscal non provisionné |
| **Conclusion** | Dettes jugées exhaustives si l'analytique est cohérente avec les attentes et si les rapprochements sont soldés |

⚠️ Le livre cite DSN, CET, DADS2 : références françaises. Équivalents marocains (CNSS, retenues à la source, etc.) : **À vérifier dans la réglementation marocaine en vigueur**.

**❓ Question** : *« Comment auditez-vous les dettes sociales ? »*
**✅ Réponse** : « Je fixe d'abord mes attentes : effectif, hausses, primes. Je compare avec les charges de personnel et le taux de charges apparent, je rapproche les dettes des déclarations, je teste la cohérence taux × assiette et je regarde les paiements après clôture pour valider les dettes estimées. »

## 5.11 TVA (outil 54)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | La TVA collectée déclarée correspond aux produits comptabilisés ; les soldes de TVA au bilan sont justes |
| **Risques principaux** | TVA collectée sous-évaluée (redressement) ; TVA déductible sur éléments non soumis ; mauvais prorata ; erreur sur les créances ou dettes de TVA ; TVA sur FNP/FAE oubliée |
| **Assertions** | Exhaustivité · Évaluation · Classification |
| **Documents** | Déclarations de TVA de l'exercice ; liste des comptes de produits ; balance auxiliaire clients ; états de FNP, FAE, avoirs |
| **Procédures** | 1. **Rapprochement TVA collectée / produits** : obtenir toutes les déclarations ; lister les comptes de produits ; distinguer soumis / non soumis ; reconstituer ; expliquer les écarts.<br>2. **Soldes de bilan** : TVA à décaisser ou crédit de TVA ↔ dernière déclaration ; TVA sur FNP/FAE par cohérence ; TVA sur encaissements ↔ TVA incluse dans les comptes de tiers (clients − avoirs à émettre).<br>3. Maîtriser les écarts classiques : TVA sur les débits ou encaissements, intracommunautaire, export, prorata de déduction.<br>4. Si l'entité ne fait pas de rapprochement : le proposer en lettre de recommandation |
| **Anomalies recherchées** | Écart non expliqué entre CA comptable et CA déclaré ; crédit de TVA anormal ; TVA déduite sur frais non déductibles |
| **Conclusion** | Si les écarts sont expliqués : assurance raisonnable sur la TVA collectée et les soldes de bilan |

⚠️ Le livre parle de la déclaration **CA3** (France), de **TVA sur les débits** et d'opérations intracommunautaires. **Régimes, taux, périodicité et prorata au Maroc : À vérifier dans la réglementation marocaine en vigueur.**

**❓ Question** : *« Qu'est-ce qu'un rapprochement de TVA ? »*
**✅ Réponse** : « Je rapproche le chiffre d'affaires et les autres produits comptabilisés de la base déclarée à la TVA, en séparant ce qui est soumis et ce qui ne l'est pas, et j'explique chaque écart : décalages d'exigibilité, exports, avoirs. Puis je rapproche les soldes de TVA du bilan avec la dernière déclaration. »

## 5.12 Charges, produits et séparation des exercices (outils 27, 47)

| Élément | Contenu |
|---|---|
| **Objectif d'audit** | Chaque charge et chaque produit est dans le **bon exercice** ; comptes de régularisation exacts |
| **Risques principaux** | FNP ou FAE oubliées ; CCA sans réalité ; PCA sous-estimés ; abonnements annuels non étalés ; manipulation du résultat |
| **Assertions** | Séparation des exercices · Exhaustivité · Existence (CCA) · Évaluation |
| **Documents** | Journaux ; contrats pluriannuels (assurances, loyers, maintenance) ; calculs de prorata ; listes de FNP/FAE/CCA/PCA |
| **Procédures** | 1. Comprendre l'activité et le niveau attendu de régularisation.<br>2. **Cut-off** achats/ventes (partie 4.4).<br>3. **CCA/PCA** : recalcul du prorata sur contrat, tests de détail sur les principaux, calculs de cohérence.<br>4. Rapprocher FNP/FAE avec les réceptions et livraisons de fin d'année.<br>5. Revue analytique des postes de charges récurrentes (assurance, loyers) |
| **Anomalies recherchées** | Charge annuelle payée en décembre sans CCA ; prestation de décembre facturée en janvier sans FAE |
| **Conclusion** | Séparation des exercices correcte si les écarts de cut-off sont soldés ou régularisés |

Dans le même esprit pour les **autres créances et autres dettes** 📘 (outil 44 : poste « fourre-tout » à risque élevé) : détail de tous les éléments, entretiens avec le service comptable, justificatifs (contrat, facture, relevé), réconciliation des comptes courants, recouvrabilité et confirmation de solde si nécessaire. Chaque élément a son propre risque : classification à vérifier.

**❓ Question** : *« Comment testez-vous la séparation des exercices sur les charges ? »*
**✅ Réponse** : « Je prends les factures de janvier et février, je regarde la date de réception ou de réalisation du service et je vérifie que celles qui concernent décembre sont en FNP. Je vérifie aussi, pour les charges payées d'avance, que le prorata a bien été calculé et qu'une CCA a été constatée. »

---

# 6. Revue analytique et continuité d'exploitation
*(Livre : Dossier 7, outils 55 à 58)*

## 6.1 Revue analytique du bilan, du compte de résultat et du tableau de flux — outils 55 à 57

**Définition à retenir** 📘 : analyse des **fluctuations de chaque poste** par rapport aux attentes de l'auditeur (connaissance de l'entité), qui sert aussi de **base de dialogue** avec le dirigeant. Elle **ne remplace jamais** les tests de détail.

**Étapes** 📘

| Document | Démarche |
|---|---|
| **Bilan** | Comparer N/N-1 → expliquer les variations (**ou l'absence de variation**) → points d'attention : trésorerie nette/endettement net et solidité par rapport aux capitaux propres ; **BFR** par rapport à l'activité (croissance du CA → hausse du BFR) ; investissements et financements ; provisions. Prévoir les covenants. Échanger avec le dirigeant |
| **Compte de résultat** | Comparer postes (exploitation / financier / non courant) → cohérence avec historique, budget, benchmark : **marge** (CA vs achats), **charges externes** (variables vs fixes), **frais de personnel** (vs CA, embauches) → demander les actions menées et leur traduction comptable → challenger les explications (pas de « journalisme ») |
| **Tableau de flux** | Trois catégories : **activité** (résultat, amortissements, provisions, variation du BFR), **investissement** (acquisitions rapprochées du tableau d'immobilisations, cessions rapprochées du prix), **financement** (dividendes et capital rapprochés des PV, emprunts rapprochés du tableau des dettes). La trésorerie d'ouverture et de clôture doit **cadrer avec le bilan** (concours bancaires courants inclus). L'affacturage va en flux de financement, pas dans le BFR |

**Règles du livre** 📘 : fixer ses **attentes avant** de comparer ; seuls les points **significatifs** sont documentés ; ne pas chercher à justifier toute variation jusqu'à une pièce ; conclusion dans la note de synthèse ; confier le bilan à un auditeur expérimenté.

**Exemple** : CA +10 % mais charges de personnel +25 %. Attente : +10 % plus quelques hausses. Explications à demander : embauche de commerciaux au S2 (effet CA l'an prochain), prime exceptionnelle. Vérifier avec les effectifs et les états de paie.

**❓ Question** : *« Comment expliquez-vous une variation anormale d'un compte ? »*
**✅ Réponse** : « Je fixe d'abord mon attente, par exemple l'évolution du CA ou de l'effectif, puis je mesure l'écart. J'interroge la direction sur l'origine, je vérifie l'explication avec des pièces ou un autre indicateur et je fais des tests de détail si l'écart est significatif. Si je n'arrive pas à l'expliquer, je le signale au chef de mission. »

## 6.2 Continuité d'exploitation — outil 58

**Définition à retenir** 📘 : principe selon lequel l'entité établit ses comptes en **poursuivant son activité** sur la période suivant la clôture (12 mois pour l'arrêté des comptes). L'auditeur apprécie le risque, en continu pendant l'exercice, et en tire **toutes** les conséquences.

**Pourquoi c'est critique** 📘 : un actif peut avoir une valeur en exploitation (une machine) et aucune hors exploitation (non revendable).

**Étapes** 📘
1. Entretien avec la direction.
2. Prise de connaissance des **budgets** et prévisions.
3. Revue de l'évolution de la **trésorerie** et de l'**endettement**.
4. Revue des **comptes prévisionnels** (si obligatoires).
5. Documenter dans la note de synthèse ou un mémo dédié.
6. Conclure : observation, réserve, refus de certifier, mise en œuvre de la procédure d'alerte, selon le cas.

**Conseils** 📘 : privilégier l'approche **économique** (perte d'un contrat) à l'approche comptable ; contacter régulièrement le dirigeant ; ne pas prendre ses explications pour argent comptant ; **ne pas rester attentiste** si un risque est identifié.

**Signaux 🧠** : pertes récurrentes, capitaux propres inférieurs à la moitié du capital (à vérifier au Maroc), retards de paiement fournisseurs, covenants rompus, perte d'un client majeur, trésorerie nette négative persistante.

**❓ Question** : *« Que faites-vous si vous doutez de la continuité d'exploitation ? »*
**✅ Réponse** : « J'examine les plans d'action de la direction : budget de trésorerie, financements obtenus, engagements de soutien de l'actionnaire. Si l'incertitude persiste mais est correctement exposée en annexe, je la mentionne dans mon rapport ; si les comptes sont établis en continuité alors qu'elle n'est pas appropriée, je modifie mon opinion. Je peux aussi déclencher la procédure d'alerte prévue par la loi. »

⚠️ La **procédure d'alerte** décrite par le livre (outil 59 : phases, délais de 8 à 30 jours, président du tribunal de commerce) est celle du droit français. Au Maroc, le mécanisme relève de la **loi 73-17** : voir partie 13 (statut de vérification).

---

# 7. Définitions et distinctions à mémoriser

## 7.1 Définitions fondamentales

| Notion | Définition à retenir | Origine |
|---|---|---|
| **Audit financier / objectif** | Examen indépendant des états financiers pour exprimer une opinion avec une **assurance raisonnable** qu'ils ne comportent pas d'anomalies significatives | 🧠 |
| **Anomalie significative** | Information inexacte, insuffisante ou omise, du fait d'erreurs ou de fraude, d'une importance telle que, **seule ou cumulée**, elle peut influencer le jugement de l'utilisateur | 📘 |
| **Assertions** | Critères dont la réalisation conditionne la régularité, la sincérité et l'image fidèle des comptes (réalité, exhaustivité, mesure, séparation des exercices, classification, existence, droits et obligations, évaluation, présentation) | 📘 |
| **Seuil de signification (matérialité)** | Montant au-delà duquel une anomalie peut influencer les décisions des utilisateurs ; sert aussi à fixer les seuils d'investigation | 📘 |
| **Risque inhérent** | Possibilité d'une anomalie significative **en l'absence de contrôle interne** (probabilité × impact) | 📘 |
| **Risque lié au contrôle** | Risque que le contrôle interne ne prévienne ni ne détecte l'anomalie | 📘 |
| **Risque de non-détection** | Risque que les procédures de l'auditeur ne détectent pas une anomalie significative existante ; **le seul que l'auditeur règle** par l'étendue de ses travaux | 🧠 |
| **Risque d'anomalies significatives (RAS)** | Combinaison risque inhérent × risque lié au contrôle, par compte et assertion | 📘 |
| **Risque de fraude** | Risque d'anomalie résultant d'un **acte intentionnel** (détournement d'actifs ou manipulation des états financiers) | 📘 |
| **Élément probant** | Information collectée par l'auditeur pour fonder son opinion ; plus fiable quand elle est **externe, indépendante et obtenue directement** (circularisation > déclaration orale) | 🧠 (esprit du livre) |
| **Sondage d'audit** | Technique qui sélectionne un échantillon d'une population pour conclure sur l'ensemble ; chaque élément doit pouvoir être sélectionné | 📘 |
| **Cut-off** | Test de la **séparation des exercices** : date de comptabilisation vs date du fait générateur | 📘 |
| **Circularisation** | Demande de confirmation directe à un tiers indépendant | 📘 |
| **Documentation d'audit** | Ensemble de dossiers (permanent, de travail) qui formalise démarche et travaux, avec piste d'audit, pour justifier l'opinion | 📘 |
| **Continuité d'exploitation** | Hypothèse selon laquelle l'entité poursuit son activité sur les 12 mois suivant l'arrêté des comptes | 📘 |
| **Piste d'audit** | Chemin documenté du chiffre aux pièces, grâce au référencement croisé | 📘 |
| **Suspens** | Point non résolu (pièce manquante) qui empêche de conclure | 📘 |

## 7.2 Distinctions à connaître

**Audit externe / interne / contrôle interne** 🧠

| | Audit externe | Audit interne | Contrôle interne |
|---|---|---|---|
| **Qui** | Auditeur indépendant (CAC) | Service de l'entreprise | Direction et collaborateurs |
| **Objectif** | Opinion sur les états financiers | Évaluer et améliorer la maîtrise des risques et des processus | Prévenir et détecter les erreurs et fraudes |
| **Destinataires** | Tiers, actionnaires | Direction, comité d'audit | Direction |
| **Lien** | S'appuie sur le contrôle interne et peut utiliser des travaux de l'audit interne | | Évalué par l'auditeur pour fixer l'étendue des tests |

**Test de contrôle vs contrôle de substance** 📘🧠

| | Test de contrôle | Contrôle de substance |
|---|---|---|
| **Cible** | Efficacité du dispositif | Exactitude des montants des comptes |
| **Échantillon** | Standard (25, 5, 2, 2, 1) | Selon seuils et risques |
| **Si anomalie** | Contrôle déficient, risque de contrôle élevé | Ajustement comptable |
| **Preuve apportée** | Le processus fonctionne | Le solde est correct |

**Test de détail vs procédure analytique** : voir 4.0.

**Existence vs exhaustivité (réflexe clés)** 📘

| Poste | Assertion principale | Réflexe de test |
|---|---|---|
| Actifs (clients, stocks, immobilisations) | **Existence** et évaluation | Partir du **compte** vers la pièce |
| Passifs (fournisseurs, provisions, dettes) | **Exhaustivité** et évaluation | Partir de la **réalité** vers le compte (cut-off, circularisation ouverte, revue subséquente) |

**Circularisation fermée vs ouverte** 📘 : fermée = on indique le montant (clients) ; ouverte = le tiers indique son montant (fournisseurs).

**Valeur brute / VNC / valeur actuelle** 📘 : VNC = valeur comptable ; valeur actuelle = max (valeur vénale, valeur d'usage) ; dépréciation si valeur actuelle < VNC.

**FNP / FAE / CCA / PCA** : voir tableau 4.4.

---

# 8. Questions d'entretien transversales
*(Les questions propres à chaque notion sont dans les parties 2 à 6.)*

**1. Vous trouvez une anomalie de 40 000 MAD, sous le seuil. L'ignorez-vous ?**
Non. Je la consigne dans la liste des anomalies, je la **cumule** avec les autres, j'apprécie sa nature (fraude ? opération inhabituelle ?) et je la signale au chef de mission. Elle figurera dans les ajustements non corrigés et dans la lettre d'affirmation.

**2. Que signifie « assurance raisonnable » ?**
Un niveau d'assurance élevé mais non absolu, parce que l'auditeur teste par sondage, selon des seuils, et que le contrôle interne et le jugement ont des limites.

**3. Pourquoi ne pas tester 100 % des opérations ?**
Impossible et inutile : on cible les comptes significatifs et les risques. Là où l'analyse de données le permet, on teste toute la population.

**4. Comment décidez-vous de tester ou non les contrôles ?**
Je regarde le volume de transactions, l'automatisation, la complexité, le risque de fraude et le gain d'efficacité. Sans contrôle fiable, j'adopte une approche substantive avec un risque de contrôle élevé.

**5. La direction refuse de vous communiquer un document ou limite vos travaux. Que faites-vous ?**
Je relance, j'escalade au chef de mission, je cherche une procédure alternative ; si la limitation persiste et que je ne peux pas conclure, elle a des conséquences sur mon opinion. Un refus de signer la lettre d'affirmation est un signal d'alarme.

**6. Le client conteste un ajustement. Comment réagissez-vous ?**
Je présente les faits (pièces, calcul), l'effet sur le résultat et la norme appliquée. Si l'écart reste inférieur au seuil, il peut rester non corrigé mais figure dans la liste des ajustements non corrigés ; sinon j'en tire les conséquences sur l'opinion.

**7. Quel poste vous semble le plus sensible ?**
La **trésorerie** (poste sensible, pas de seuil) et les postes à jugement : **provisions**, **dépréciations**, **valorisation des stocks**. Et le **chiffre d'affaires**, avec présomption de fraude.

**8. Pourquoi la balance auxiliaire ne suffit-elle pas à auditer les clients ?**
Elle sert de base de sélection et de rapprochement, mais vient du même système comptable. La preuve vient des pièces externes : confirmation, encaissements, livraisons.

**9. Pourquoi tester les écritures manuelles de fin de période ?**
Parce que c'est un moyen classique de manipuler le résultat (risque de contournement des contrôles par la direction). Je recherche les écritures inhabituelles, en fin de période, sans libellé clair ou avec des montants ronds.

**10. Que faites-vous si vous suspectez une fraude ?**
Je ne confronte pas seul : j'en informe immédiatement le chef de mission, j'étends mes procédures, je documente, et la direction du cabinet décide des suites (obligations de signalement : **À vérifier dans la réglementation marocaine en vigueur**).

**11. Qu'est-ce qu'un test de cheminement ?**
Suivre une transaction de bout en bout pour confirmer ma compréhension du processus et des contrôles ; les contrôles revus peuvent compter dans l'échantillon des tests de contrôle, mais ce test seul ne prouve pas l'efficacité des contrôles.

**12. Vous avez peu d'heures budgétées : que sacrifiez-vous ?**
Rien de ce qui couvre un risque élevé. J'alerte le chef de mission pour réallouer ; j'évite de sur-auditer les comptes à faible RAS.

**13. Quelle différence entre cut-off et circularisation ?**
Le cut-off teste la **date** de comptabilisation (séparation des exercices) à partir de pièces internes ; la circularisation obtient la **confirmation d'un tiers** sur un solde (existence ou exhaustivité). Elles se complètent et se remplacent partiellement en cas de non-réponse.

**14. Pourquoi utiliser des procédures analytiques en phase finale ?**
Pour avoir une vision d'ensemble : détecter des incohérences non vues dans les tests détaillés et vérifier la cohérence des comptes avec ma connaissance de l'entité.

**15. Qu'avez-vous appris de vos stages qui est utile pour l'audit ?**
Question de profil : appuyez-vous sur vos expériences bancaires et comptables (rapprochements, analyse du risque de crédit, états financiers), en les reliant à une procédure précise : rapprochement bancaire, balance âgée, évaluation de provisions.

---

# 9. Mini-cas pratiques corrigés

> Les montants sont fictifs. Les écritures n'utilisent pas de numéros de compte (non vérifiés).

## Cas 1 — Seuil de signification
**Énoncé** : RCAI = 6 000 000 MAD ; l'entité est stable et rentable. Quel seuil proposer ? Et si le résultat était négatif, avec un CA de 80 M ?
**Correction** : taux de 3 à 10 % sur le RCAI ; risque moyen → **5 %** → **300 000 MAD**. Si résultat négatif ou volatil, agrégat inadapté : CA à 0,5 à 3 % ; avec 1 % → **800 000 MAD**. On documente le choix de l'agrégat et du taux. Fourchettes françaises : à confronter au manuel OEC ou à la pratique du cabinet.

## Cas 2 — Écart de circularisation clients
**Énoncé** : Solde comptable du client Z = 120 000 ; réponse du client = 100 000. Écart 20 000. Que faites-vous ?
**Correction** : demander l'extrait de compte du client et rapprocher.
- **Hypothèse A** : règlement de 20 000 émis le 29/12 par le client, encaissé le 5/01 → écart de **décalage** ; je confirme par le relevé bancaire post-clôture → **pas d'anomalie**.
- **Hypothèse B** : facture de 20 000 émise le 30/12 pour un bien livré le 3/01 → **anomalie de cut-off** : produit N surévalué de 20 000 → proposer un ajustement (produit constaté d'avance) et étendre le test de cut-off sur les ventes de fin d'année.

## Cas 3 — Cut-off achats
**Énoncé** : Marchandises reçues le 28/12/N pour 120 000 HT ; facture reçue et comptabilisée le 5/01/N+1 ; aucune FNP. Seuil = 300 000.
**Correction** : le fait générateur (réception) est en N ; la charge est donc à comptabiliser en N.

| Écriture proposée (31/12/N) | Débit | Crédit |
|---|---|---|
| Achats de marchandises (ou variation de stock selon le système) | 120 000 | |
| Fournisseurs – factures non parvenues | | 120 000 |

Effet : résultat N diminué de 120 000 ; dette augmentée de 120 000. **Inférieur au seuil isolément**, mais à cumuler avec les autres anomalies ; alerter sur la qualité du cut-off et étendre l'échantillon si d'autres cas apparaissent.

## Cas 4 — Rapprochement bancaire
**Énoncé** : relevé bancaire au 31/12 : 912 500 ; chèques émis non débités : 75 000 ; remise déposée le 31/12 non créditée : 10 000 ; solde comptable : 845 000.
**Correction** :
- Solde bancaire ajusté = 912 500 − 75 000 + 10 000 = **847 500**.
- Écart avec la comptabilité : 847 500 − 845 000 = **2 500** → opération en banque **non comptabilisée** (ex. virement client reçu).
- Écriture à passer : Débit Banque 2 500 / Crédit Clients 2 500 (après identification du client).
- Contrôles : apurement des chèques et de la remise sur le relevé de janvier ; ancienneté des chèques (ici récents) ; libellé du virement de 2 500 ; confirmation bancaire.

**Conclusion** : écart expliqué, une régularisation à comptabiliser ; aucune alerte si l'apurement de janvier est confirmé.

## Cas 5 — Dépréciation de stock
**Énoncé** : référence X : 500 unités au coût de 40 ; prix de vente net attendu : 30. Dépréciation comptabilisée : 2 000.
**Correction** : dépréciation nécessaire = 500 × (40 − 30) = **5 000** ; insuffisance = 5 000 − 2 000 = **3 000** → ajustement proposé :

| Écriture | Débit | Crédit |
|---|---|---|
| Dotation aux dépréciations des stocks | 3 000 | |
| Dépréciation des stocks | | 3 000 |

Vérifier le prix de vente net sur des **ventes récentes** ou des offres, et la **permanence** de la méthode.

## Cas 6 — Recalcul des amortissements
**Énoncé** : machine de 240 000 mise en service le 1er juillet N, linéaire 8 ans. Dotation comptabilisée : 30 000.
**Correction** : dotation attendue = 240 000 ÷ 8 × 6/12 = **15 000** ; surcharge de **15 000** (année pleine appliquée au lieu du prorata).

| Écriture | Débit | Crédit |
|---|---|---|
| Amortissements cumulés | 15 000 | |
| Dotation aux amortissements | | 15 000 |

Étendre le test aux autres acquisitions de l'exercice (erreur de méthode probable).

## Cas 7 — Balance âgée et dépréciation
**Énoncé** : seuil d'investigation 50 000 HT. Le client D doit 100 000 HT depuis 150 jours, sans provision. Le dirigeant dit : « il paiera, c'est un gros client ». Une recherche indique que D est en difficulté.
**Correction** :
1. Chercher des encaissements post-clôture (aucun).
2. Demander les échanges avec D et un plan de paiement écrit.
3. Examiner la situation financière de D.
4. Sans preuve de recouvrabilité, **proposer une dépréciation** (jusqu'à 100 000 HT selon le risque), même si la direction craint de « reconnaître » l'impayé.
5. Lien avec le risque de continuité d'exploitation si D est un client majeur.

## Cas 8 — Sondage SUM
**Énoncé** : stock 1 M€, 3 000 lignes ; 15 lignes spécifiques = 330 K€ ; erreur acceptable 20 000 €, coefficient 1,2.
**Correction** : population hors éléments spécifiques = 670 000. Taille ≈ 670 000 × 1,2 ÷ 20 000 ≈ **40** lignes. Pas = 670 000 ÷ 40 ≈ **16 667 €**. Tirer au sort la première ligne, puis une ligne à chaque pas. Total à tester : 40 + 15 = **55** références.

## Cas 9 — Variation anormale de marge
**Énoncé** : CA 10 M → 11 M (+10 %) ; achats consommés 6 M → 6,12 M (+2 %). Marge brute : 40 % → 44,4 %.
**Correction** : l'écart est trop favorable. Hypothèses : **oubli de factures** (cut-off, exhaustivité des dettes), stock final surévalué, changement de mix ou de prix, erreur de classement. Travaux : cut-off achats, FNP, revue subséquente des décaissements, test de valorisation et inventaire, entretien sur les prix et le mix. Conclusion à tirer seulement après explication chiffrée.

## Cas 10 — Revue subséquente
**Énoncé** : décaissements de janvier > 30 000 : A) 45 000 facture de **décembre**, aucune FNP ; B) 60 000 facture de janvier ; C) 38 000 assurance annuelle de N+1 payée en janvier.
**Correction** : A) dette omise de 45 000 → FNP à comptabiliser, charge N ; B) rattaché à N+1, aucune action ; C) charge N+1, aucune action. Ajustement net : **45 000**. Étendre le contrôle si d'autres décaissements de décembre apparaissent.

---

# 10. Liste des notions à apprendre par cœur

**Assertions**
- Flux : Réalité · Exhaustivité · Mesure · Séparation des exercices · Classification
- Soldes : Existence · Droits et obligations · Exhaustivité · Évaluation et imputation
- Actif → existence + évaluation ; Passif → exhaustivité + évaluation

**Risques**
- RAS = RI × RC ; grille : élevé/élevé = maximum ; faible/faible = minimum ; élevé/faible = moyen ; faible/élevé = moyen
- Risque d'audit = RI × RC × RND
- Présomption de fraude sur les produits

**Tests de contrôle** : journalier 25, hebdomadaire 5, mensuel 2, trimestriel 2, annuel 1, applicatif 1 ; erreur sur journalier : 25 → 40 (1 erreur) → 60 (2 erreurs) ; autre fréquence : 1 erreur = déficient

**Circularisation** : 6 étapes (sélection, liste, envoi par l'auditeur, suivi, exploitation, alternatives) ; clients = fermée ; fournisseurs = ouverte ; banques = exhaustif ; avocats = litiges

**Cut-off** : 2 mois avant et après ; fait générateur ; FNP, FAE, CCA, PCA

**Revue subséquente** : max 3 mois ; seuil bas si risque élevé ; objectif = exhaustivité des dettes

**Stocks** : CUMP, FIFO ; part matière souvent > 80 % ; dépréciation = coût − valeur probable de réalisation

**Capitaux propres** : variation = capital, résultat, provisions réglementées, changement de méthode

**Continuité** : 12 mois ; entretien, budgets, trésorerie/endettement, prévisions ; ne pas rester attentiste

**Feuille de travail** : objectif, travaux, résultats, conclusion ; 4 types de conclusion

**Référencement** : dans les deux sens ; une feuille non référencée n'existe pas

---

# 11. Checklist finale de préparation à l'entretien

- [ ] Je peux définir en 20 secondes : audit, assertion, seuil, RAS, élément probant, sondage
- [ ] Je récite les assertions et je sais lesquelles prioriser à l'actif et au passif
- [ ] Je sais construire la grille RAS de mémoire et en tirer l'étendue des travaux
- [ ] Je sais expliquer test de contrôle vs test de détail vs procédure analytique
- [ ] Je peux dérouler pas à pas : circularisation, cut-off, rapprochement bancaire, revue subséquente, inventaire physique
- [ ] Je peux répondre à « que faites-vous concrètement ? » pour les 12 cycles de la partie 5
- [ ] Je sais traiter une non-réponse de circularisation, une pièce manquante, un écart inexpliqué
- [ ] Je maîtrise 3 calculs : seuil, amortissement au prorata, taille d'échantillon (SUM)
- [ ] Je connais les 4 écritures de régularisation : FNP, FAE, CCA, PCA
- [ ] Je sais citer le cadre marocain essentiel : OEC, CGNC, normes alignées sur les ISA (avec le statut de vérification de la partie 13)
- [ ] J'ai préparé 2 exemples de mes stages que je peux relier à une procédure d'audit
- [ ] J'ai repéré les références françaises à ne pas transposer (⚠️)

---

# 12. Sujets secondaires et limites de lecture

## 12.1 À étudier ensuite (priorités 2 et 3)

| Sujet (outil) | Pourquoi | Statut de lecture |
|---|---|---|
| Dossier 1 : normes, déontologie, documentation professionnelle, notes d'information, acceptation, blanchiment (1 à 6) | Cadre de la profession ; **ignoré à votre demande** (acceptation vue en 5 lignes seulement dans la partie 1) | Outils 1 à 5 lus en diagonale, non repris ; outil 6 survolé |
| Communication avec l'équipe et le client, réunion de synthèse (12, 14, 15) | Savoir-faire relationnel | **Non lus** |
| Environnement IT et contrôles généraux informatiques (33) | Condition pour s'appuyer sur les contrôles applicatifs | Début lu |
| Utilisation des travaux d'un tiers / expert (34) | Gain de temps | Introduction lue |
| Immobilisations incorporelles R&D (37) | 6 critères de capitalisation | Introduction lue ; schéma des critères **non lu** |
| Écarts de conversion (46) | Transactions en devises | Introduction lue |
| Comptes de régularisation (47) | Voir 5.12 | Début lu |
| Procédure d'alerte (59) et revue indépendante (60) | Droit français ; équivalent marocain à vérifier | Lus, non repris en détail |
| Dossier 8 : consolidation (61 à 67) | Instructions d'audit, tableau de variation des capitaux propres consolidés, contrats de location, impôts différés, preuve d'impôt, revue croisée | Introductions et outils 62 et 67 en partie ; **le reste non lu** |
| Glossaire | Acronymes uniquement | Lu |

## 12.2 Limites de lecture du PDF

- **Pages 120 à 125** (suite de l'outil 22 sur le calcul des seuils) : **vides**, même en image.
- **Pages 164, 204 et 239** : sans texte extractible ; **non vérifiées visuellement** (probablement des tableaux ou corrigés d'exemples).
- Les **schémas** de début d'outil et plusieurs tableaux sous forme d'image n'ont été lus que pour la grille RAS (p. 111), les taux de seuils (p. 119) et le tableau de tests de contrôle (p. 109).
- Les exemples dont le corrigé est en image ont été **reconstitués** à partir des règles du livre (mention explicite quand c'est le cas).

---

# 13. Sources et compléments marocains

## 13.1 Équivalences de vocabulaire France → Maroc

| Livre (France) | Équivalent à utiliser au Maroc | Statut |
|---|---|---|
| PCG / ANC / CRC | **CGNC** (Code général de normalisation comptable) et PCGE | Vérifié (sources secondaires) |
| Compte de résultat | **CPC** (compte de produits et charges) ; charges exceptionnelles → **charges non courantes** | Vérifié (sources secondaires) |
| NEP / H3C / CNCC | Normes d'audit de l'**OEC**, alignées sur les ISA ; pas d'autorité d'audit indépendante selon l'IFAC | Vérifié (IFAC) |
| CAC (commissaire aux comptes, diplôme DEC/CAFCAC) | CAC inscrit au tableau de l'**Ordre des experts-comptables** | Vérifié (sources secondaires) |
| Procédure d'alerte (loi de 1984) | Prévention des difficultés (loi **73-17**) : alerte du CAC | Partiellement vérifié |
| DSN, DADS2, CET, CA3, loi LME, loi Pacte, Dailly, Tracfin | Pas d'équivalent direct à retenir sans vérification | **À vérifier dans la réglementation marocaine en vigueur** |

## 13.2 Compléments marocains (statut de vérification)

| Point | Contenu | Statut | Source consultée |
|---|---|---|---|
| Profession d'expert-comptable | Loi **15-89** (dahir 1-92-139, 1993) instituant l'**OEC** | Vérifié par une source internationale | IFAC (profil OEC Maroc) ; mémoire universitaire |
| Normes d'audit | L'OEC a adopté des normes marocaines d'audit alignées sur les **ISA** ; **manuel des normes d'audit PME** (octobre 2019) ; **contrôle qualité** obligatoire prévu par la loi 15-89 | Vérifié (IFAC) ; manuel PME rapporté par un cabinet | IFAC ; Upsilon Consulting |
| Société anonyme | **Loi 17-95** : un CAC obligatoire en SA ; inscription à l'OEC (**art. 160**) ; incompatibilités (**art. 161**) ; nomination pour **trois exercices** (**art. 163**) | Cohérent entre plusieurs sources secondaires ; **texte officiel non consulté** | Upsilon Consulting ; supports universitaires |
| SNC et SARL | Renvoi à la loi 17-95 par la loi **5-96** (art. 13 et 83) ; **seuil de 50 M DH** évoqué pour la SARL | **Source unique** : À vérifier dans la réglementation marocaine en vigueur | Upsilon Consulting |
| Comptabilité | **Loi 9-88** (obligations comptables des commerçants) ; **CGNC** ; 5 états de synthèse | Vérifié (loi 9-88 citée par le ministère des Finances) ; liste des 5 états à confirmer | finances.gov.ma ; Upsilon Consulting |
| Plan comptable | Classes : 1 financement permanent, 2 actif immobilisé, 3 actif circulant, 4 passif circulant, 5 trésorerie, 6 charges, 7 produits, 8 résultats. Exemples de comptes : 1111 capital social, 3421 clients, 4411 fournisseurs, 5141 banques, 6111 achats revendus de marchandises, 7111 ventes de biens | Vérifié (sources secondaires concordantes) | Upsilon Consulting ; support de cours |
| Difficultés des entreprises | Loi **73-17** (2018) : prévention, conciliation, sauvegarde ; alerte du CAC en cas de faits compromettant la continuité | Principe vérifié ; **numéros d'articles, délais et dates de publication non vérifiés** (les sources divergent sur les dates) | Upsilon Consulting ; TelQuel ; article universitaire |

## 13.3 Points sans vérification — ne pas citer en entretien sans contrôle

- Seuils de signification et taux : **À vérifier dans la réglementation marocaine en vigueur** (les fourchettes du livre sont françaises).
- Délais de paiement légaux (équivalent de la LME) : **À vérifier dans la réglementation marocaine en vigueur**.
- TVA (taux, périodicité, prorata, exigibilité), impôt sur les sociétés, retenues à la source, CNSS : **À vérifier dans la réglementation marocaine en vigueur**.
- Règle de dotation de la réserve légale et seuil d'alerte sur les capitaux propres : **À vérifier dans la réglementation marocaine en vigueur**.
- Obligations de signalement en cas de fraude : **À vérifier dans la réglementation marocaine en vigueur**.

**Sources officielles à consulter en priorité** : Ordre des experts-comptables du Maroc (OEC) pour les normes d'audit ; Secrétariat général du gouvernement et Bulletin officiel pour les textes de loi ; Direction générale des impôts pour la fiscalité ; Conseil national de la comptabilité pour le CGNC.

**Note méthodologique** : les compléments marocains proviennent d'un cabinet d'expertise (Upsilon Consulting), de supports universitaires, du profil IFAC de l'OEC et d'une page du ministère des Finances. Aucun texte de loi n'a été lu dans sa version officielle. Les numéros d'articles indiqués sont ceux rapportés par ces sources.

---

*Fin du document — Cours_pratique_audit_financier_PFE_Maroc.md*
