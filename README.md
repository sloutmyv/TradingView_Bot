# TradingView Binance Bot Project

## Langage de programation
Installer le langage [Python](https://www.python.org/downloads/)
## Editeur de texte
Installer l'éditeur [Visual studio](https://code.visualstudio.com/) 
## Github
Pour chaque nouveau projet créer un répertoire directement depuis le [GitHub](https://github.com/)
### Les commandes à connaitre 
Pour cloner un répertoire existant depuis github : 
```
git clone <url>
```
Pour afficher la liste des fichiers/dossiers modifiés : 
```
git status
```
Pour ajouter des fichiers/dossiers non inclus : 
```
git add <fichier/dossier>
git add .
```
Pour créer un commit : 
```
git commit -m “description du commit”
```
Pour uploader les modifications sur github (sur la branche master) : 
```
git push origin master
```
Pour extraire mettre à jour le dossier depuis githup : 
```
git fetch origin
```
Pour fusionner depuis github : 
```
git pull
```
Pour lister les commits (taper q pour quitter) : 
```
git log 
```
### Le fichier ".gitignore"
Il est créé à la racine du projet pour indiquer les fichier à ne pas upload sur le répertoire github en ligne, à inclure (pour un projet Django):
```
# Environments
.env
.venv
env/
venv/
ENV/
env.bak/
venv.bak/
```
## Environnement virtuel
Installer le package d’environnement virtuel : 
```
pip3 install virtualenv
```
Creer l’environnement virtuel : 
```
python3 -m venv <virtual-environnement-name>
```
Activer l’environnement virtuel : 
- Linux/Mac :
```
source <virtual-environnement-name>/bin/activate
```
Désactiver l’environnement virtuel :
``` 
deactivate
```