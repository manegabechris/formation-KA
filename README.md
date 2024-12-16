Git, GitHub et GitHub Pages
Introduction à Git et GitHub
Objectifs d’apprentissage
- Comprendre les commandes de base de Git et le concept de gestion de version.

- Apprendre les workflows GitHub pour la collaboration.

- Déployer des sites statiques avec GitHub Pages.

Pré-requis
- Connaissances de base en HTML.

- Notions de base sur le terminal ou ligne de commande.

- Visual Studio Code est installé.

Git : Qu’est-ce que c’est et pourquoi l’utiliser ?
- Suivi des modifications du code.

- Collaboration entre développeurs.

- Facilité à revenir à une version précédente en cas d’erreurs.

GitHub :
Qu’est-ce que c’est et pourquoi l’utiliser ?

GitHub est une plateforme pour héberger et gérer des dépôts Git.

Fonctionnalités principales
- Hébergement centralisé des dépôts.

- Outils de collaboration : Pull requests, revue de code, gestion des issues.

- Hébergement gratuit pour sites statiques via GitHub Pages.

Workflow Git et GitHub :
Schéma du workflow :
img
Mise en place de l’environnement

Installation de Git
Téléchargez Git à partir de [https://git-scm.com].
Suivez les instructions d’installation : - [Installation sur Windows, Mac et Linux] (https://www.simplilearn.com/tutorials/git-tutorial/git-installation-on-windows)
Vérifiez l’installation : git --version
Création d’un compte GitHub
Accédez à github.com.
Cliquez sur Sign up.
Remplissez les champs requis (e-mail, mot de passe, nom d’utilisateur).
Confirmez votre adresse e-mail.
Configuration de Git avec GitHub
Configurez les informations utilisateur :
git config --global user.name "Votre Nom"

git config --global user.email "votre.email@example.com"

Outils recommandés
IDE : Visual Studio Code (déjà installé).

Commandes Git de base
Initialisation d’un dépôt Git
Commande : git init
Exemple pratique : Initialiser un dépôt dans un dossier projet. Staging et commit des modifications
Staging : git add .
Commit : git commit -m "Votre message"
Analogie : Le staging prépare les modifications, le commit les sauvegarder. Branching et fusion
Créer une branche : git branch feature-branch
Basculer sur une branche : git checkout feature-branch
Fusionner les branches : git merge feature-branch Push et pull
Envoyer des modifications sur GitHub : git push origin main
Récupérer des modifications de GitHub : git pull origin main
Création d’un dépôt sur GitHub
Nouveau dépôt
Sur GitHub, cliquez sur New Repository.
Remplissez les options : Nom, description, public/privé, README. Connecter un dépôt local à GitHub
Commandes : git remote add origin https://github.com/utilisateur/repository.git git push -u origin main
Cloner un dépôt existant - Exemple : git clone https://github.com/utilisateur/repository.git
Création d’un site statique simple Préparation HTML/CSS - Exemple : `index.html` :
ka formation
