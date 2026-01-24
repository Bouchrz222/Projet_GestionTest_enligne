# Application de Gestion des Tests en Ligne

Application web complète permettant la **gestion, le passage et l’évaluation de tests en ligne**, destinée aux candidats et aux administrateurs.  
Elle propose une interface moderne, un système de sessions chronométrées et un suivi détaillé des résultats.

---

## Vidéo de démonstration
**Lien de la vidéo (présentation & démonstration de l’application)** :  
https://drive.google.com/file/d/1hOA7i1qP5j4WcGkqLdG1kN_qvDDUH-uR/view?usp=drive_link

---

## Fonctionnalités principales

### Espace Candidat
- Inscription et connexion sécurisées
- Consultation et choix des créneaux disponibles
- Passage des tests avec **timer automatique**
- Calcul automatique du score et du pourcentage
- Affichage des résultats à la fin du test
- Récupération du code de session par email

### Espace Administrateur
- Gestion des candidats
- Gestion des tests et des sessions
- Gestion des questions
- Visualisation et suivi des résultats
- Tableau de bord administratif

---

## Technologies utilisées

### Backend
- **Jakarta EE**
- **WildFly**
- **JPA / Hibernate**
- **API REST**

### Frontend
- **React.js**
- **React Router**
- **Axios**
- **CSS / Tailwind CSS**

### Base de données
- **MySQL**
- **XAMPP**

---

## Structure du projet

```text
Projet_GestionTest_enligne/
│
├── backend/        # Backend Jakarta EE (API REST)
├── frontend/       # Frontend React
├── database/       # Scripts SQL
│   └── schema.sql  # Schéma de la base de données
└── README.md

Réalisé par
Bouchra Azirar
