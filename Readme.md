### Étapes pour utiliser GIT

#### 1. Initialisation du dossier GIT

* Exécutez la commande `git init` pour initialiser GIT dans le dossier actuel (une seule fois puis plus jamais besoin pour ce dossier de travail).

#### 2. Ajout des modifications pour la prochaine version

* Exécutez la commande `git add .` pour ajouter toutes les modifications faites depuis la dernière version (ou toutes les modifs si aucune version) pour la prochaine version.

#### 3. Création d'une nouvelle version

* Exécutez la commande `git commit -m "Message de version"` pour créer une nouvelle version avec comme nom de version le message apres le `-m`.

#### 4. Envoi des versions sur github.com

* Si vous n'avez pas déjà ajouté le repository distant :
	+ Exécutez la commande `git remote add origin urlDuRepoGithub`.
* Pour envoyer vos versions sur github.com :
	+ Exécutez la commande `git push -u origin main` (puis `git push` tout court pour les prochaines fois).
