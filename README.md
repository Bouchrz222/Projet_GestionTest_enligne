# Application de Gestion des Tests en Ligne

## Description
Cette application permet de gérer des tests en ligne pour des candidats, avec un suivi des résultats et une interface d'administration complète.

- **Backend** : Jakarta EE (WildFly)
- **Frontend** : React.js
- **Base de données** : MySQL (XAMPP)
- **Communication** : REST API

## Modules principaux
1. **Gestion des candidats** : Inscription, connexion, choix de créneaux
2. **Gestion des tests** : Passage des tests avec timer automatique
3. **Gestion des résultats** : Calcul et affichage des résultats
4. **Administration** : Gestion des questions, paramètres et visualisation des tests

## Installation
1. Installer XAMPP et activer MySQL
2. Importer le schéma de la base de données (`database/schema.sql`) et les données initiales (`database/data.sql`)
3. Démarrer le backend Jakarta EE (déployer le WAR généré par Maven)
4. Démarrer l'application React

## Démarrage rapide

### Backend (Jakarta EE)
1. Installer WildFly
2. Déployer le fichier WAR
3. Configurer la base de données MySQL

### Frontend (React)
```bash
cd frontend
npm install
npm start


