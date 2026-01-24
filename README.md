# Application de Gestion des Tests en Ligne

Application web complète permettant la **gestion, le passage et l’évaluation de tests en ligne**, destinée aux candidats et aux administrateurs.  
Elle offre une interface moderne, un système de sessions de test chronométrées et un suivi détaillé des résultats.

---

## 🎥 Vidéo de démonstration

👉 **Lien de la vidéo (présentation & démonstration)** :  
https://drive.google.com/file/d/1hOA7i1qP5j4WcGkqLdG1kN_qvDDUH-uR/view?usp=drive_link

---

## Fonctionnalités principales

### Espace Candidat
- Inscription et authentification sécurisée
- Consultation des créneaux disponibles
- Passage des tests avec **timer automatique**
- Affichage du score et du pourcentage final
- Récupération du code de session par email

### Espace Administrateur
- Gestion des candidats
- Gestion des tests et des sessions
- Gestion des questions (QCM, vrai/faux, etc.)
- Consultation et suivi des résultats
- Tableau de bord administratif

---

## Architecture & Technologies

### Backend
- **Jakarta EE**
- **WildFly**
- **JPA / Hibernate**
- **RESTful API**

### Frontend
- **React.js**
- **React Router**
- **Axios**
- **Tailwind CSS / CSS**

### Base de données
- **MySQL**
- **XAMPP**

---

## Structure du projet

```text
Projet_GestionTest_enligne/
│
├── backend/        # Application Jakarta EE (API REST)
├── frontend/       # Application React
├── database/       # Scripts SQL (schéma + données)
│   |__ schema.sql
└── README.md
