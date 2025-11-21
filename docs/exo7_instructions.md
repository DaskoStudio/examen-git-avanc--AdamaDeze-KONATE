Exercice 7 - stash
Commandes utilisées (exemples):
- `git add docs/exo7.md` : préparer le fichier (index)
- `git reset HEAD docs/exo7.md` : enlever l'ajout pour garder le fichier modifié non indexé
- `git stash push -m "WIP exo7" docs/exo7.md` : mettre les modifications de côté (stash)
- `git stash list` : lister les stash
- `git checkout main` puis `git checkout dev` : changer de branche
- `git stash pop` : restaurer le stash
Ces commandes mettent de côté un travail en cours et permettent de changer de branche sans committer.
