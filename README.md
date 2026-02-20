# 📘 GitHub Pédagogique

Support de cours progressif, interactif et participatif dédié aux élèves de **Bac Pro CIEL**, **BTS CIEL** et **BTS SIO**.

---

## 🎯 Objectifs pédagogiques

Ce projet permet aux élèves de :

- Comprendre les fondamentaux de **Git** et **GitHub**
- Maîtriser les commandes Git essentielles
- Publier un projet sur GitHub
- Déployer un site web en ligne via **Netlify**
- Travailler en autonomie sur un projet réel
- Valider leurs acquis grâce à un QCM final

L’approche est progressive, concrète et orientée pratique.

---

## 🚀 Installation du projet

### 🔧 Prérequis

Avant de commencer, assurez-vous d’avoir installé :

- Node.js 18 ou supérieur  
- Git  
- Un compte GitHub  
- Un compte Netlify (gratuit)

---

### 💻 Installation en local

1️⃣ Cloner le dépôt

    git clone https://github.com/votre-nom/github-pedagogique.git
    cd github-pedagogique

2️⃣ Installer les dépendances

    npm install

3️⃣ Lancer le serveur de développement

    npm run dev

Le site sera accessible à l’adresse :

    http://localhost:4321

---

## 🌍 Déploiement sur Netlify

### ✅ Méthode recommandée : via l’interface Netlify

1. Créez un compte sur https://www.netlify.com  
2. Connectez-vous avec votre compte GitHub  
3. Cliquez sur **Add new site → Import an existing project**  
4. Sélectionnez le dépôt GitHub  
5. Configurez le build :
   - Build command : `npm run build`
   - Publish directory : `dist`
6. Cliquez sur **Deploy site**

---

### 💻 Méthode alternative : via la ligne de commande

    # Installer Netlify CLI
    npm install -g netlify-cli

    # Se connecter à Netlify
    netlify login

    # Déployer en production
    netlify deploy --prod

---

## 📂 Structure du projet

    github-pedagogique/
    ├── src/
    │   ├── layouts/
    │   │   └── Layout.astro
    │   ├── pages/
    │   │   ├── index.astro
    │   │   ├── cours.astro
    │   │   └── qcm.astro
    │   └── styles/
    │       └── global.css
    ├── public/
    │   └── images/
    ├── astro.config.mjs
    ├── tailwind.config.mjs
    ├── package.json
    └── README.md

---

## ✨ Fonctionnalités

- ✅ Cours progressif et interactif  
- ✅ Exercices pratiques intégrés  
- ✅ QCM final de 20 questions  
- ✅ Sauvegarde automatique des réponses (localStorage)  
- ✅ Reprise de session possible  
- ✅ Envoi des résultats par email  
- ✅ Design responsive  
- ✅ Déploiement automatique sur Netlify  

---

## 🎓 Utilisation pédagogique

Ce support est conçu pour :

1. Être utilisé en autonomie ou en classe
2. Servir de base de manipulation Git réelle
3. Permettre une évaluation formative via le QCM
4. Encourager la publication et le déploiement d’un projet complet

Les élèves peuvent envoyer leurs résultats à l’adresse :

**mormin@st-nicolas.fr**

---

## 🛠️ Technologies utilisées

- Astro — Framework web moderne orienté performance  
- Tailwind CSS — Framework CSS utilitaire  
- Netlify — Hébergement et déploiement continu  

---

## 👨‍🏫 Auteur

**Eric MORMIN**  
Email : mormin@st-nicolas.fr  
Site : https://www.ekmconseils.eu  

Ressource pédagogique réalisée pour  
La Salle Saint-Nicolas — Issy-les-Moulineaux  

Formations concernées :  
- Bac Pro CIEL  
- BTS CIEL  
- BTS SIO  

---

## 📝 Licence

© 2026 Eric MORMIN — Tous droits réservés  

Édité par Luca HALLET  

---

**Version 1.0.0**