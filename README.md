# README.md

## Description du Projet
EPYTODO est une application Todo construite en utilisant Node.js. Ce projet se concentre sur le développement du backend, avec la possibilité d'ajouter un frontend en bonus. L'objectif principal est de permettre aux utilisateurs de gérer facilement leurs tâches à faire.

## Structure du Projet
Le projet doit respecter une structure spécifique pour assurer une organisation efficace :
- **src**: dossier principal du projet.
- **package.json**: fichier contenant les informations sur l'application et ses dépendances.
- **config**: contient les fichiers de connexion à la base de données.
- **index.js**: fichier principal qui lance l'application.
- **middleware**: contient les middlewares créés pour gérer les requêtes.
- **routes**: contient les sous-dossiers avec les routes nécessaires pour le projet.
- **.env**: fichier contenant les variables de configuration essentielles.

## Installation
Pour installer et exécuter le projet localement, suivez ces étapes :
1. Cloner le dépôt depuis GitHub.
2. Installer les dépendances en exécutant `npm install`.
3. Configurer les variables d'environnement dans un fichier `.env`.
4. Importer le schéma de la base de données en utilisant le fichier `epytodo.sql`.
5. Lancer l'application avec `npm start`.

## Routes Disponibles
Voici la liste des routes disponibles dans le projet :
- **/register**: POST pour enregistrer un nouvel utilisateur.
- **/login**: POST pour connecter un utilisateur.
- **/user**: GET pour afficher les informations d'un utilisateur.
- **/user/todos**: GET pour afficher les tâches d'un utilisateur.
- **/todos**: GET pour afficher toutes les tâches, POST pour créer une tâche.
- **/todos/:id**: GET pour afficher une tâche spécifique, PUT pour mettre à jour, DELETE pour supprimer.

## Technologies Utilisées
Le projet EPYTODO utilise les technologies suivantes :
- Express
- mysql2
- dotenv
- jsonwebtoken
- bcryptjs

## Auteur
Ce projet a été développé par Jean-Baptiste VIOSSI, Aïmane ALASSANE et Deschanel MONDOTÉ.