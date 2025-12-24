"# git_test" 

'''
Installer Git


Dans github :

1) Créer un repository

2) Lui donner un nom et un descriptif


Configurations diverses dans le terminal git :

1) Obtenir la version de git: git --version

2) Changer de repertoire: cd <chemin>

3) Générer un clé ssh : ssh-keygen -t rsa -b 4096 -C jauresfotsa@gmail.com

4) Voir les fichiers créés : dir C:\Users\hp\.ssh

5) Afficher la clé publique RSA : more C:\Users\hp\.ssh\id_rsa.pub

6) Settings -> SSH keys and GPG keys -> New SSH Key
	Coller la clé publique

7) Identité :
	git config --global user.email "jauresfotsa@gmail"
	git config --global user.name "Fotsa-Mbogne"

8) 

NB:	"Fotsa-Mbogne" est le nom du compte.


Créer un repository :

1) Changer de repertoire vers le dossier de projet : cd <chemin>

2) Initialiser : git init

3) Ajout du fichier : git add <file>

4) Faire un commit : git commit -m "Initial commit"

5) Créer ue branche : git branch -M main

6) Connexion distante avec github : git remote add origin git@github.com:Fotsa-Mbogne/git_test.git

7) Faire un push : git push -u origin main

8) Voir la configuration : code .git/config

9) Voir le statut git : git status


Faire un dépôt sur github : 

1) git remote add origin git@github.com:Fotsa-Mbogne/git_test.git

2) git branch -M main

3) git push -u origin main


Cloner un repository depuis le terminal git :

1) Obtenir la version de git: git --version

2) Changer de repertoire: cd <chemin>

3) Cloner un projet : git clone <URL> <Nouveau nom>

'''