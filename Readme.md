- 1ere chose à faire dans un nouveau dossier de travail :
- git init 
- Ca permet d'initialiser GIT dans le dossier actuel.

2eme chose : 
- git add .
- Permet d'ajouter toutes les modifications faites depuis la dernière version (ou toutes les modifs si aucune version) pour la prochaine version.

3 eme chose :
- git commit -m "Message de version"
- Va créer une nouvelle version avec comme nom de version le message apres le -m

Si ça n'as pas encore été fait :
- git remote add origin urlDuRepoGithub

4 eme chose :
- git push -u origin main (puis git push tout court pour les prochaines fois)
Permet d'envoyer nos versions chez github.com