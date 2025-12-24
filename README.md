"# git_test" 
'''
Installer Git

Dans github :

1) Créer un repository

2) Lui donner un nom et un descriptif


Configurations diverses dans le terminal git :

1) Obtenir la version de git: git --version

2) Changer de repertoire: cd <chemin>

3) Cloner un projet : git clone <URL> <Nouveau nom>

4) Générer un clé ssh : ssh-keygen -t rsa -b 4096 -C jauresfotsa@gmail.com

5) Voir les fichiers créés : dir C:\Users\hp\.ssh

6) Afficher la clé publique RSA : more C:\Users\hp\.ssh\id_rsa_Test.pub

7) Settings -> SSH keys and GPG keys -> New SSH Key
	Coller la clé publique
	

Créer un repository :

1) Changer de repertoire vers le dossier de projet : cd <chemin>

2) Initialiser : git init

3) Connexion distante avec github : git remote add origin git@github.com:Fotsa-Mbogne/git_test.git

4) Voir la configuration : code .git/config

5) Voir le statut git : git status

6) Ajout du fichier : git add <file>
'''