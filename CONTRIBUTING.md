# Contribuer à Starlight Octalist

## Convention de commits

Ce projet suit [Conventional Commits](https://www.conventionalcommits.org/).

Format : `<type>(<scope>): <description>`

Types autorisés :
- `feat`     : nouvelle fonctionnalité
- `fix`      : correction de bug
- `docs`     : documentation (GDD, README, commentaires)
- `art`      : ajout/modification d'assets graphiques
- `audio`    : ajout/modification d'assets sonores
- `refactor` : réécriture sans changement de comportement
- `test`     : ajout/modification de tests
- `chore`    : tâches diverses (config, gitignore, etc.)

Scopes suggérés :
- `player`   : déplacement, stats, inputs
- `combat`   : système de combat
- `dialogue` : système de dialogue, PNJ
- `ui`       : menus, HUD, inventaire
- `map`      : 
- `save`     : sauvegarde/chargement
- `audio`    : musique, sons
- `gdd`      : document de design
- `readme`   : documentation racine
- `repo`     : structure du dépôt, config

Exemples :
- `feat(combat): ajout du menu Attaquer/Fuir`
- `fix(player): collision avec les murs du donjon`
- `docs(gdd): précision sur la mécanique principale`
- `art(sprite): ajout animation idle du héros`

## Workflow Git

- Branche principale : `main`
- Pour une nouvelle fonctionnalité : `feat/kebab-case`
- Pour un bug : `fix/kebab-case`
- Commits atomiques (un commit = un changement cohérent)
- Une branche par fonctionnalité, pas par session
- Rebase ou merge avant de pousser
- Revue par un pair avant merge sur `main` ou `develop` (même informelle)
- Push à la fin de chaque session **sur `develop`**, pas sur `main`

## Convention de nommage des fichiers

- Minuscules, tirets, sans accents, sans espaces : `gdd.md`, `lore.md`, `mvp-doc.md`.
- Exception : les fichiers `README.md` conservent leur nom en majuscules (convention universelle, reconnaissance GitHub).
- Les fichiers sources (`docs/sources/`) suivent la même convention.
- Les branches suivent le kebab-case : `feat/combat-tour-par-tour`, `fix/collision-murs`.

## Fichiers en lecture seule
Le dossier [`docs/sources/`](docs/sources/) contient les textes originaux de Rigeau.
**Ne pas modifier.** Toute correction passe par l'auteur.
Voir [docs/sources/README.md](docs/sources/README.md).