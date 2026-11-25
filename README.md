# Plateforme-de-gestion-de-projets-informatiques

## 1. Présentation du projet

Plateforme collaborative de gestion de projets informatiques : équipes, tâches, communication, tableaux de bord, diagrammes techniques et intégration GitHub.

L'application repose sur une architecture microservices, permettant de séparer les différentes fonctionnalités en services indépendants, facilitant ainsi leur développement, leur maintenance et leur évolution.

## 2. Architecture du projet

L'application est organisée autour de plusieurs microservices, chacun responsable d'un domaine fonctionnel précis.

### 2.1. Microservice Authentification et Sécurité (Abdelali)

**Responsabilités :**

- Inscription et connexion des utilisateurs.

- Authentification basée sur JWT.

- Gestion des rôles et des permissions.

- Sécurisation des accès aux différents services.

- Centralisation des requêtes via l'API Gateway.

**Technologies :** Java, Spring Boot, Spring Security, JWT.

### 2.2. Microservice Gestion des Projets et des Équipes (Rabie)

**Responsabilités :**

- Création, modification et suppression des projets.

- Gestion des membres des équipes.

- Invitation et intégration de nouveaux membres.

- Gestion des stacks technologiques utilisées dans les projets.

**Technologies :** Java, Spring Boot, REST API.

### 2.3. Microservice Gestion des Tâches (Nada)

**Responsabilités :**

- Création et gestion des tâches.

- Organisation des tâches sous forme de tableau Kanban.

- Gestion des priorités et des types de tâches.

- Affectation et auto-affectation des tâches.

- Suivi de l'historique des modifications.

**Technologies :** Java, Spring Boot, REST API.

### 2.4. Microservice Dashboards et Gestion des Problèmes (Hafsa)

**Responsabilités :**

- Affichage des statistiques des projets.

- Visualisation de la progression à travers des graphiques.

- Suivi de l'avancement des équipes.

- Déclaration et suivi des problèmes rencontrés.

- Centralisation des informations relatives aux projets.

**Technologies :** Java, Spring Boot, REST API.

### 2.5. Microservice Communication (Khaoula)

**Responsabilités :**

- Messagerie instantanée entre les membres.

- Communication en temps réel.

- Gestion des notifications.

- Communication vocale (fonctionnalité optionnelle).

**Technologies :** Java, Spring Boot, WebSocket, REST API.

### 2.6. Microservice Conception et Gestion des Diagrammes (Fatine)

**Responsabilités :**

- Création et édition graphique des diagrammes.

- Manipulation des éléments avec Drag & Drop.

- Sauvegarde et modification des diagrammes.

- Validation et publication des diagrammes.

**Technologies :** JavaFX, bibliothèque graphique JavaFX.

### 2.7. Microservice Intégration GitHub et Génération Automatique (Ali)

**Responsabilités :**

- Connexion avec les comptes et dépôts GitHub.

- Intégration avec l'API GitHub.

- Importation et exportation des données.

- Génération automatique de diagrammes à partir de bases de données MySQL.

**Technologies :** Java, Spring Boot, GitHub REST API, MySQL.

## 3. Technologies utilisées

| Besoin | Technologie |
| --- | --- |
| Interface Desktop | JavaFX |
| Backend | Java, Spring Boot |
| Communication entre services | REST API |
| Communication instantanée | WebSocket |
| Base de données | MySQL |
| Conteneurisation | Docker, Docker Compose |
| API Gateway | Spring Cloud Gateway |
| Authentification | Spring Security, JWT |
| Intégration GitHub | GitHub REST API |
| Conception des diagrammes | Bibliothèque graphique JavaFX |

## 4. Architecture technique

L'application suit une architecture distribuée organisée autour des composants suivants :

- **Client Desktop :** interface utilisateur développée avec JavaFX.

- **API Gateway :** point d'entrée centralisé pour les requêtes vers les microservices, utilisant Spring Cloud Gateway.

- **Microservices Backend :** services indépendants développés avec Java et Spring Boot.

- **Communication REST :** échanges de données entre le client et les services.

- **WebSocket :** gestion des communications instantanées.

- **Base de données MySQL :** stockage des données de l'application.

- **Docker Compose :** orchestration et lancement des différents composants dans des conteneurs.

## 5. Conteneurisation et déploiement

Le projet utilise Docker et Docker Compose afin de simplifier le lancement et la gestion de l'environnement technique.

La conteneurisation permet notamment de :

- Standardiser l'environnement d'exécution.

- Faciliter le démarrage des différents services.

- Simplifier la configuration et le déploiement.

- Assurer une meilleure reproductibilité de l'environnement de développement.

## 6. Objectifs du projet

Les principaux objectifs de cette plateforme sont :

- Centraliser la gestion des projets informatiques.

- Améliorer la collaboration entre les développeurs.

- Faciliter la répartition et le suivi des tâches.

- Offrir une communication instantanée entre les membres.

- Visualiser l'avancement des projets.

- Simplifier la conception et la documentation technique.

- Faciliter l'intégration avec GitHub et les outils de développement.

---

**Projet :** Plateforme Collaborative de Gestion de Projets Informatiques  
**Architecture :** Microservices  
**Langage principal :** Java  
**Framework Backend :** Spring Boot

