# Voyage Maroc CAN 2025 🇲🇦🦁

Page web pour planifier le voyage au Maroc pour la CAN 2025.

## 📋 Instructions pour publier sur GitHub Pages

### Étape 1 : Créer un dépôt GitHub

1. Allez sur [GitHub.com](https://github.com) et connectez-vous
2. Cliquez sur le bouton **"+"** en haut à droite, puis **"New repository"**
3. Nommez votre dépôt (ex: `voyage-maroc-can-2025`)
4. Cochez **"Public"** (nécessaire pour GitHub Pages gratuit)
5. **Ne cochez PAS** "Initialize with README" (vous avez déjà les fichiers)
6. Cliquez sur **"Create repository"**

### Étape 2 : Initialiser Git et pousser les fichiers

Ouvrez un terminal dans ce dossier et exécutez :

```bash
# Initialiser Git (si pas déjà fait)
git init

# Ajouter tous les fichiers
git add .

# Faire le premier commit
git commit -m "Initial commit: Page voyage Maroc CAN 2025"

# Ajouter le dépôt distant (remplacez USERNAME et REPO_NAME)
git remote add origin https://github.com/USERNAME/REPO_NAME.git

# Pousser vers GitHub
git branch -M main
git push -u origin main
```

### Étape 3 : Activer GitHub Pages

1. Allez sur votre dépôt GitHub
2. Cliquez sur **"Settings"** (en haut du dépôt)
3. Dans le menu de gauche, cliquez sur **"Pages"**
4. Sous **"Source"**, sélectionnez **"Deploy from a branch"**
5. Choisissez la branche **"main"** et le dossier **"/ (root)"**
6. Cliquez sur **"Save"**

### Étape 4 : Accéder à votre site

Après quelques minutes, votre site sera disponible à l'adresse :
```
https://USERNAME.github.io/REPO_NAME/
```

Par exemple : `https://sidyfelixbadji.github.io/voyage-maroc-can-2025/`

## 🔄 Mettre à jour le site

Chaque fois que vous modifiez le fichier `index.html`, faites :

```bash
git add index.html
git commit -m "Mise à jour du planning"
git push
```

Le site se mettra à jour automatiquement en quelques minutes !

## 📝 Notes

- Le fichier `index.html` est la page principale
- GitHub Pages sert automatiquement `index.html` à la racine
- Les modifications peuvent prendre 1-2 minutes pour apparaître en ligne

