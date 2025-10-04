# Carnet EPS (MVP)
Application web 100% locale pour créer des classes (import Pronote CSV/texte), faire l'appel, saisir des notes (/20), garder des mémos et générer des groupes.

## Utilisation
- Ouvrir `index.html` (double-clic) — tout marche hors ligne.
- **Créer mes classes** : entrer un nom, **coller** la liste Pronote _ou_ **importer** un fichier `.csv/.tsv/.txt`.
- Les données restent dans le **LocalStorage** de votre navigateur (RGPD).

## Déploiement GitHub Pages
- Poussez `index.html` à la racine du dépôt (`main`), puis activez **Settings → Pages** (Deploy from a branch, Folder: `/`).

## Export/Archive
- Dans **Gérer mes classes**, exportez une archive JSON de toutes vos données et restaurez-la quand vous voulez.
