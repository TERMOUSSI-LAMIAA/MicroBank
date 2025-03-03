✨ Modernisation d'une Infrastructure Bancaire - Microservices avec Spring Boot & Spring Cloud ✨

🌐 Description du Projet

Une banque souhaite moderniser son infrastructure IT en développant une application backend basée sur une architecture microservices. Cette application permettra de gérer les clients et leurs comptes bancaires (courant et épargne) via des API REST.

💡 Backend : Spring Boot, Spring Cloud (Eureka, Config, Gateway), Spring Data JPA

🛠️ Communication inter-services : RestTemplate

📂 Base de données : SGBD relationnel (ex: PostgreSQL, MySQL...)

✅ Tests : JUnit, Mockito

🎨 Architecture : Architecture en couches avec les design patterns (Repository, DTO, ...)

🎮 Architecture Microservices

Le système est divisé en 5 microservices :

Customer Service (👤) : Gestion des clients

Account Service (💳) : Gestion des comptes et opérations

Gateway Service (🏡) : Point d'entrée unique API (Spring Cloud Gateway)

Discovery Service (🌍) : Service discovery (Eureka)

Config Service (📁) : Configuration centralisée (stockée dans un repository Git local ou distant)


🛠️ Fonctionnalités par Service

👤 Customer Service

➕ Ajouter un client

🔍 Lister tous les clients

🔍 Rechercher un client par ID

📂 Persistance des données avec Spring Data JPA

💳 Account Service

➕ Créer un compte

🔍 Consulter un compte

🔍 Lister les comptes d'un client

👤 Communication avec Customer Service via RestTemplate

⏳ Démarrage du Projet

1.Cloner le projet :

      git clone https://github.com/TERMOUSSI-LAMIAA/MicroBank.git
2.Démarrer les services dans l'ordre :

     Lancer Eureka Discovery Service
     Lancer Config Service
     Lancer Customer Service
     Lancer Account Service
     Lancer Gateway Service

3.Accéder aux services :

Eureka Dashboard : http://localhost:8761

API Gateway : http://localhost:8080

Customer Service : http://localhost:8081

Account Service : http://localhost:8082

Auteur et Informations de Contact:

    Termoussi Lamiaa 
    Email: lamiaa3105@gmail.com
