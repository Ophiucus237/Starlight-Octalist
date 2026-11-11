# Starlight Octalist

> Action-RPG, side-scroller, ~5h de jeu, en développement.

## Statut
🚧 En développement — Jour 11 (phase initiale)

## Pitch

Voir [Pitch](docs/gdd.md#pitch) dans le GDD.

## Stack
- **Git + GitHub** (conventional commits)
- **VS Code**
- **SFML** pour le rendu et les entrées

## Structure du repo
```text
projet_1/
├── README.md           ← ce fichier
├── CONTRIBUTING.md     ← guide de contribution
│
├── docs/
│   ├── reunion
│   │   └── .gitkeep
│   ├── gdd.md          ← Game Design Document
│   ├── roadmap.md      ← plan de progression
│   ├── journal.md      ← log quotidien
│   ├── bestiaire.md    ← Encyclopédie interne des créatures, ennemis et boss
│   ├── lore.md         ← Lore
│   ├── mvp-doc.md      ← Le doc de MVP
│   ├── vsdd.md         ← Le Vertical Slice Design Doc
│   └── sources/
│       ├── README.md
│       ├── synopsis-du-jeu.md
│       ├── le-garcon-au-bandeau.md
│       ├── le-loup-des-champs.md
│       └── viktor-orstem.md
│
├── scripts/
│   ├── src/            ← fichiers .cpp
│   │   ├── main.cpp
│   │   ├── Player.cpp
│   │   ├── Platform.cpp
│   │   └── Camera.cpp
│   │
│   └── include/        ← fichiers .h
│       ├── Player.h
│       ├── Platform.h
│       └── Camera.h
│
└── assets/
    ├── sprites/
    │   └── .gitkeep
    │
    ├── audio/
    │   └── .gitkeep
    │
    └── fonts/
        └── .gitkeep
```

## Contrôles
- **ZQSD / WASD / Flèches** : déplacement
- **E / Espace** : interagir (à venir)

## Roadmap
Voir [docs/roadmap.md](docs/roadmap.md)

## Journal de développement
Voir [docs/journal.md](docs/journal.md)

## Contribuer
Voir [CONTRIBUTING.md](CONTRIBUTING.md)

## Licence

> À définir avec l'équipe.

[MIT/GPL v3/CC BY-NC-SA/autre] — voir [LICENSE](LICENSE)