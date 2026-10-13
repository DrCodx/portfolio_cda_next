# Git & Portfolio

Ici on a créée un portfolio en HTML & CSS et on l'a push sur Github.

## Comment push un projet en local sur Github ?

### Etape 1 : Installer Git sur sa machine
```bash
sudo apt-get update
sudo apt install git
```
Avec ces 2 commandes, on installe git sur notre machine. On le fait une fois pour toutes.

### Etape 2 : Initialiser le projet git
On se localise sur le projet qu'on veut envoyer sur github, puis
```bash
git init
```
Cette commande va initialiser un projet git

### Etape 3 : On commit (sauvegarde) notre projet
```bash
git add . # Ca va selectionner l'entiereté du dossier où on est
git commit -m "Premier commit !" # Ca va commit (sauvegarder) tout les éléments qu'on a add (séléctionner)
```

### Etape 4 : On push sur le serveur distant (donc sur Github)
```bash
git push
```