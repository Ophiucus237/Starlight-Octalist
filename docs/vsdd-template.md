# Vertical Slice Design Doc : Starlight Octalist

**Date :** 2026-11-09\
**Durée cible de la tranche :** [ex. 5–10 minutes de jeu continu]\
**Source GDD :** [GDD.md](gdd.md)

## 1. Objectif de la tranche (Slice Goal)

[Une phrase. Ex. : « Prouver qu'un joueur ressent [fantasme central] en 10 minutes, avec la qualité visuelle et sonore finale, et que l'équipe peut produire à ce niveau. »]

## 2. Parcours d'expérience

| Étape | Action du joueur | Réponse du système | Ce que cela prouve |
|:---|:---|:---|:---|
| 1 | [ex. Entrer dans la zone] | [ex. Déclenchement de la musique et de l'UI] | [L'ambiance est posée] |
| 2 | [ex. Premier combat] | [ex. Feedback de coup, sons, particules] | [Le combat est lisible et satisfaisant] |
| 3 | [ex. Victoire] | [ex. Récompense visuelle/sonore] | [La boucle de récompense fonctionne] |

## 3. Périmètre construit (Build Scope)

| Couche | Inclus | Exclu | Raison de l'exclusion |
|:---|:---|:---|:---|
| **Mécaniques** | [ex. Combat complet] | [ex. Arbre de compétences] | [Non nécessaire pour prouver le fun] |
| **Contenu** | [ex. 1 niveau, 3 types d'ennemis] | [ex. 10 niveaux] | [Concentration sur la qualité] |
| **Art/Audio** | [Qualité finale représentative] | [Assets non critiques] | [Prouver la direction artistique] |
| **UI/UX** | [Interface finale du HUD] | [Menus de réglages avancés] | [Prouver la lisibilité] |
| **Tech** | [Pipeline de build cible] | [Optimisations non critiques] | [Prouver la faisabilité technique] |

## 4. Hypothèses à prouver (Must-Prove Assumptions)

| Hypothèse | Pourquoi c'est critique | Critère Pass | Critère Fail |
|:---|:---|:---|:---|
| [ex. Le feedback de combat est lisible] | [Sans lisibilité, le jeu n'est pas fun] | [4/5 testeurs décrivent l'impact sans qu'on leur demande] | [Les testeurs ne remarquent pas les coups] |
| [ex. L'équipe peut produire à ce niveau] | [Détermine la faisabilité du projet] | [La tranche est construite dans le temps imparti] | [Dépassement > 50 %] |

## 5. Protocole de playtest

| Cible | Tâche | Observation | Question à poser |
|:---|:---|:---|:---|
| [ex. 5 testeurs externes n'ayant pas vu le jeu] | [Jouer la tranche sans aide] | [Temps jusqu'à la première action, points de blocage] | [« Décrivez ce que vous avez ressenti pendant le combat. »] |

## 6. Critères Go / Observe / Pivot / Stop (écrits à l'avance)

| Décision | Condition | Action |
|:---|:---|:---|
| **Go** | [Toutes les hypothèses Pass + qualité perçue comme représentative] | Lancer la production complète |
| **Observe** | [Résultats ambigus sur 1 hypothèse] | Prolonger les tests ou ajuster le périmètre |
| **Pivot** | [La qualité est atteinte mais le fun ne l'est pas] | Revoir la boucle, pas les assets |
| **Stop** | [L'équipe ne peut pas reproduire cette qualité dans un temps raisonnable] | Arrêt ou réduction drastique du scope |

## 7. Journal de vélocité (à remplir après construction)

| Jour | Ce qui a été accompli |
|:---|:---|
| 1 | [ex. Setup du projet, placeholder du niveau] |
| 2 | [ex. Combat jouable en cubes gris] |
| 3 | [ex. Intégration des assets finaux du personnage] |

**Vélocité estimée :** [ex. « 1 jour par type d'ennemi, 0.5 jour par écran d'UI »]

## 8. Décision finale (à remplir après playtest)

**Recommandation :** [PROCEED / PIVOT / KILL]\
**Justification :** [Référencer directement la question de validation et les observations]\
**Prochaine étape :** [Lien vers le plan de production]