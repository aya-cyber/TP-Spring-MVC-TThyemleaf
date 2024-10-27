TP : Application Web CRUD avec Spring Boot et Thymeleaf
Description
Ce projet est une application Web qui illustre les fonctionnalités de gestion de données en utilisant le framework Spring Boot et le moteur de templates Thymeleaf. Il permet de gérer une liste d’utilisateurs avec les opérations CRUD (Créer, Lire, Mettre à jour, Supprimer), en intégrant Spring Data JPA pour la persistance des données. L’objectif est de mettre en œuvre une architecture MVC avec Spring, facilitant la création d’interfaces utilisateur dynamiques et la gestion des entités persistantes.

Fonctionnalités
Gestion des informations utilisateurs.
Opérations CRUD complètes pour la création, lecture, mise à jour et suppression d’enregistrements.
Utilisation de Spring Data JPA pour simplifier la gestion des opérations de persistance.
Thymeleaf comme moteur de templates pour le rendu dynamique des pages HTML.
Interface utilisateur permettant une interaction fluide avec les données stockées en base.

Technologies Utilisées
Java
Spring Boot pour l’architecture et la gestion des dépendances
Spring Data JPA pour l'abstraction des transactions SQL et la manipulation des entités
Thymeleaf pour le rendu des pages dynamiques
MySQL (ou une autre base de données relationnelle) pour la gestion de la persistance
Maven pour la gestion des dépendances et du build

Prérequis
Java Development Kit (JDK) 8 ou supérieur
Maven
Base de données relationnelle (MySQL, PostgreSQL, etc.)
Un IDE compatible, tel qu’IntelliJ IDEA ou Eclipse, pour développer et exécuter le projet
Configuration de la Base de Données
Dans le fichier application.properties, configurez les informations de connexion à votre base de données :

properties
Copier le code
# Configuration de la connexion à MySQL
spring.datasource.url=jdbc:mysql://localhost:3306/gestion_users?useSSL=false
spring.datasource.username=root
spring.datasource.password=

# Configurations de JPA
spring.jpa.hibernate.ddl-auto=update
spring.jpa.show-sql=true
Note : Assurez-vous d’avoir créé la base de données avant de démarrer l’application.

Structure du Projet

https://github.com/user-attachments/assets/ab03e905-dd0d-4ccc-8b47-f9abb44fd3c6

