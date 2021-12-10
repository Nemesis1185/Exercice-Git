# Travail sur git

## Instructions

### Compte Github

* Créer un compte sur github
* Créer un jeton d'accès personnel (personal access token) dans Settings > Developer settings > Personal access tokens
* Donner un nom au jeton puis sélectionner "repo" dans "select scopes"
* Générer le token (le copier dans un fichier)

Personne A : 
* Création d'un dépôt (repository) public sur Github
* Ajouter des droits pour la ou les personnes de votre groupe dans Settings > Manage access
* Sur l'IDE créer un nouveau dossier *git* et se déplacer dans ce dossier à l'aide la commande *cd*
* Initialiser un dépôt vide avec *git init*
* Créer un fichier index.php avec un peu de code
* Faire un commit du fichier : git add -A + git commit -m "le message de votre commit"
* Changer la branche avec la commande *git branch -M main*
* Ajouter le lien entre votre dépôt git et github avec la commande *git remote add origin {adresse de votre dépôt}* (qui se termine par .git)
* Pousser les modifications vers github : *git push -u origin main*

Personne B :
* Clone le dépôt de la personne A : *git clone {adresse du dépôt}*
* Créer un fichier test.php avec un peu de code
* Dans le terminal, se déplacer dans le dossier qui a été créé par git
* Pousser le fichier test.php vers github