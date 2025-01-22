🌿 Take Care Mind - Application de Bien-être Mental et de Développement Personnel
---------------------------------------------------------------------------------

🚀 Description du Projet
------------------------

Take Care Mind est une application complète de bien-être mental et de développement personnel, conçue pour aider les utilisateurs à améliorer leur santé mentale, à développer des habitudes positives et à progresser personnellement.

🌟 Fonctionnalités Principales
------------------------------

Authentification et Gestion des Utilisateurs
--------------------------------------------

-   Inscription et connexion sécurisées
-   Profil utilisateur personnalisable
-   Suivi des progrès personnels

Modules de Développement Personnel
----------------------------------

-   Stoïcisme : Journaux et exercices sur les principes stoïciens
-   Méditation : Méditations guidées personnalisées
-   Réalisation Personnelle : Objectifs SMART et suivi des habitudes
-   Bien-être Émotionnel : Journaux émotionnels et visualisation

Fonctionnalités Avancées
------------------------

-   Motivation et inspiration
-   Communauté et interactions sociales
-   Programme éducatif interactif
-   Outils de relaxation
-   Notifications personnalisées

🛠️ Technologies Utilisées
--------------------------

Backend
-------

-   Java Spring Boot
-   Spring Security
-   PostgreSQL
-   H2 Database (développement)
-   JWT Authentication

Frontend
--------

-   React
-   React Router
-   Axios
-   Context API

Autres Outils
-------------

-   Maven
-   Docker (optionnel)
-   Git

📦 Prérequis
------------

-   Java 17+
-   Node.js 16+
-   Maven
-   PostgreSQL (production)

🚀 Installation et Configuration
--------------------------------

Backend
-------

1.  Cloner le repository

bash

`git clone https://github.com/Adrien-25/TakeCareMind.git cd TakeCareMind `

1.  Configurer la base de données

-   Développement : H2 Database (configuration automatique)
-   Production : Configurer PostgreSQL dans `application.properties`

1.  Lancer le backend

bash

`./mvnw spring-boot:run `

Frontend
--------

1.  Naviguer vers le dossier frontend

bash

`cd frontend npm  install  npm start `

🔐 Configuration des Variables d'Environnement
----------------------------------------------

Créer un fichier `.env` avec les configurations suivantes :

text

`REACT_APP_API_URL=http://localhost:8080/api JWT_SECRET=votre_secret_jwt `

🧪 Tests
--------

Backend
-------

bash

`./mvnw test  `

Frontend
--------

bash

`cd frontend npm  test  `

🚢 Déploiement
--------------

Docker (optionnel)
------------------

bash

`docker-compose up --build `

📊 Roadmap et Fonctionnalités à Venir
-------------------------------------

-   Intégration avec Google Fit
-   Mode hors-ligne
-   Abonnements premium
-   Personnalisation avancée

🤝 Contribution
---------------

1.  Forker le projet
2.  Créer une branche pour votre fonctionnalité (`git checkout -b feature/AmazingFeature`)
3.  Commiter vos modifications (`git commit -m 'Add some AmazingFeature'`)
4.  Pousser sur la branche (`git push origin feature/AmazingFeature`)
5.  Ouvrir une Pull Request

📧 Contact
----------

Adrien SCHMIDT - Lien du Projet: <https://github.com/Adrien-25/TakeCareMind.git>

📄 Licence
----------

Distribué sous la licence MIT. Voir `LICENSE` pour plus d'informations. 🌈 Take Care Mind - Prenez soin de vous, développez-vous, épanouissez-vous ! 🌈