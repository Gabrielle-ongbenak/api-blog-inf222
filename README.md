# 🌿 GabyTech : Digital Hub & Knowledge Manager
> Système de Gestion de Contenu Dynamique avec Architecture Bento et Persistance SQLite.

![Version](https://img.shields.io/badge/Version-2.0.0-f08080)
![Node](https://img.shields.io/badge/Engine-Node.js-339933)
![DB](https://img.shields.io/badge/Database-SQLite-003B57)
![UI](https://img.shields.io/badge/UI-Bento_Grid-f08080)

---

## 📋 À propos du Projet
GabyTech est une application Full-Stack conçue pour la gestion et la publication d'articles techniques. Réalisé dans le cadre de l'unité d'enseignement INF222, ce projet démontre la mise en œuvre d'une API RESTful couplée à une interface utilisateur moderne et réactive.

Le projet met l'accent sur la clarté du code, la performance de la base de données et une expérience utilisateur (UX) inspirée des standards de design de 2026.

## 🚀 Fonctionnalités Clés
* Système Bento UI : Affichage intelligent des articles avec une grille asymétrique hiérarchisée.
* Persistance Relationnelle : Utilisation de SQLite pour un stockage robuste et fiable des données.
* Dashboard Dynamique : Mise à jour en temps réel des statistiques (nombre d'articles, catégories).
* Publication Intuitive : Formulaire modal "Slide-in" avec validation de données côté client.
* Identité Visuelle Unique : Design basé sur la palette LightCoral, offrant une interface douce et haut de gamme.

## 🛠️ Stack Technique
### Backend (Cœur de l'application)
- Node.js : Environnement d'exécution JavaScript.
- Express.js : Framework web pour la gestion des routes et middlewares.
- SQLite3 : Moteur de base de données SQL léger et performant.

### Frontend (Interface)
- HTML5 & CSS3 : Utilisation de CSS Grid et Flexbox pour la structure Bento.
- Vanilla JavaScript : Manipulation du DOM et appels API via Fetch.
- Google Fonts : Intégration de *Plus Jakarta Sans* pour une typographie premium.

## 📡 Documentation de l'API REST
L'API suit les standards REST pour une communication fluide :

| Méthode | Point de terminaison | Description |
| :--- | :--- | :--- |
| GET | /api/articles | Récupère la liste complète des articles stockés. |
| POST | /api/articles | Ajoute un nouvel article (Titre, Contenu, Auteur, Catégorie). |

## 📂 Architecture du Projet
`text
.
├── src/
│   ├── index.js          # Serveur principal et logique des routes
│   └── database.js       # Configuration et schémas SQLite
├── public/
│   └── index.html        # Front-end unifié (Vue, Styles et Logique JS)
├── database.sqlite       # Fichier de base de données (généré automatiquement)
├── package.json          # Dépendances et métadonnées du projet
└── README.md             # Documentation technique (ce fichier)

## ⚙️ Installation et Lancement
Pour exécuter ce projet localement, utilisez les commandes suivantes :

`bash
# Installation des dépendances
npm install

# Lancement du serveur
node src/index.js

## 👤 Profil du Développeur
ONGBENAK GABRIELLE
* 🎓 Niveau : Étudiante en Informatique - L2 (Informatics & CS)
* 🏛️ Institution : Université de Yaoundé 1 (UY1)
* ✨ Spécialisation : Développement Front-end & UX/UX Design
* 💻 Environnement de travail : Ubuntu Linux / Node.js



