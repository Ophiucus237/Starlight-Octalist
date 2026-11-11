# MVP Doc : Starlight Octalist

**Date :** 2026-11-09\
**Version :** 0.1\
**Statut :** En rédaction

## 1. Question à valider

[Formuler comme une hypothèse testable. Ex. : « Un joueur qui n'a jamais vu le jeu comprend-il l'action principale et la décrit-il comme satisfaisante en moins de 2 minutes ? »]

## 2. Périmètre inclus (liste fermée)

| Fonctionnalité | Pourquoi elle est indispensable |
|:---|:---|
| [ex. Combat au corps à corps] | [C'est la boucle à tester] |
| [ex. Ennemi basique avec IA minimale] | [Fournit une résistance testable] |
| [ex. Écran de fin victoire/défaite] | [Permet de boucler la session] |

## 3. Périmètre exclu (explicitement)

| Fonctionnalité | Raison de l'exclusion |
|:---|:---|
| [ex. Progression permanente] | [Non nécessaire pour tester le fun immédiat] |
| [ex. Narration] | [Pollue le test de la boucle] |

## 4. Placeholders autorisés

- **Visuel :** [cubes gris, capsules, aucun asset final]
- **Audio :** [sons temporaires ou silence]
- **UI :** [texte à l'écran, pas de menus complexes]

## 5. Critères Go / No-Go (écrits à l'avance)

| Décision | Condition | Action |
|:---|:---|:---|
| **Go** | [Ex. : 3 testeurs sur 5 terminent la boucle sans aide et la décrivent comme « satisfaisante »] | Passer au Vertical Slice |
| **No-Go** | [Ex. : Les testeurs abandonnent avant la fin ou ne comprennent pas l'action] | Pivot sur la boucle ou arrêt |

## 6. Risque principal

[Le risque n°1 que ce MVP réduit. Ex. : « La boucle de combat n'est pas fun. »]

## 7. Résultat (à remplir après test)

**Date du test :** [YYYY-MM-DD]\
**Nombre de testeurs :** [N]\
**Observations :** [Faits, pas opinions]\
**Décision :** [Go / No-Go]\
**Prochaine étape :** [Lien vers le Vertical Slice Design Doc / Pivot / Arrêt]