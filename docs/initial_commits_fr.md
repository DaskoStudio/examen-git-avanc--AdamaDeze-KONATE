# Commits initiaux (en français)

Ce fichier rassemble les commits importants effectués au début du dépôt, avec leur identifiant (SHA) et un libellé en français. Vous pouvez vérifier ces commits localement avec `git log --oneline`.

- `3be0db9` — Ajout du `README` (texte d'introduction du dépôt)
- `83917b0` — Ajout du fichier `docs/exo8.md` pour l'exercice 8
- `8f26e58` — Renommage de `docs/exo8.md` en `docs/exo8v2.md`
- `a3fabcb` — Suppression de `docs/exo8v2.md` (jugé inutile)

Commits ajoutés plus tard lors de la correction et de l'organisation :

- `5c6d002` — Ajout de `docs/branches.md` (description des branches et méthode d'intégration)
- `b806159` — Ajout de `docs/objectifs.md` (but du dépôt)
- `4e7bf31` — Ajout de `.gitignore` (avec `go.mod` et `.DS_Store`)
- `f3e373f` — Simuler une erreur en production dans `README` (texte erroné : «banane»)
- `9627c74` — `hotfix/readme-correction` : correction du README et merge dans `main`

Autres références utiles :

- `96871c6` — `feature-url` : ajout de `docs/feature-url.md`
- `92ad902` — commit simulant une modification distante sur `feature-color`
- `b51d7db` — Résolution finale et fusion des modifications (conflits) dans `docs/historique.md`

Comment vérifier localement :

1. Afficher l'historique condensé :

   `git log --oneline --graph --decorate --all`

2. Voir le contenu d'un commit spécifique (ex. `3be0db9`) :

   `git show 3be0db9` 

3. Voir les fichiers à la racine et dans `docs` :

   `git ls-tree -r --name-only origin/dev | sed -n '1,200p'`

Si vous souhaitez que je traduise d'autres messages de commit en français ou que je crée un rapport plus détaillé (avec extraits de diff pour chaque commit), dites "oui, détaille" et je l'ajouterai.
