<!-- # projet_1
Jeu vidéo plateforme 2D codé en C++ -->
# projet_1

> Action-RPG, side-scroller, ~5h de jeu, en développement.

## Statut
🚧 En développement — Jour 11 (phase initiale)

## Pitch
Un groupe de chevaliers et mercenaires d'Asvaald doit retrouver les huit réincarnations des Octalists des étoiles en partant en mission secrète contre une coalition envahissante, mais l'ennemi est trop puissant et les légendes ne sont peut-être qu'un espoir illusoire. Le jeu se distingue par son mélange d'Action-RPG et de quête mystique dans un monde en guerre, avec des ennemis liés aux arcanes sombres.

## Stack
- **Git + GitHub** (conventional commits)
- **VS Code** <!-- pour les fichiers non-GDScript (Markdown, JSON) -->
- **SFML** <!-- pour le GDScript et les scènes -->

## Structure du repo
```text
projet_1/
├── README.md           ← ce fichier
├── CONTRIBUTING.md     ← guide de contribution
│
├── docs/
│   ├── reunion
│   │   └── .gitkeep
│   ├── GDD.md          ← Game Design Document
│   ├── roadmap.md      ← plan de progression
│   ├── journal.md      ← log quotidien
│   ├── Bestiaire.md    ← Encyclopédie interne des créatures, ennemis et boss
│   ├── lore.md         ← Lore
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
[MIT/GPL v3/CC BY-NC-SA/autre] — voir [LICENSE](LICENSE)