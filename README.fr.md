# ERPWatcher — Supervision de la disponibilité des applications

**Application Web Full Stack | React · Node.js · Express · PostgreSQL**

[English](README.md) | [Français](README.fr.md)

## Présentation

ERPWatcher est une application web Full Stack conçue pour surveiller les interruptions des applications, calculer leurs taux de disponibilité et faciliter le suivi de la fiabilité d'un système ERP.

L'application centralise la gestion des applications, le suivi des interruptions et la visualisation des indicateurs de disponibilité dans un tableau de bord interactif.

Ce projet personnel met en valeur mes compétences en développement Full Stack, conception d'API REST, gestion de bases de données, authentification JWT et visualisation des données.

## Fonctionnalités principales

### Authentification et sécurité
- Authentification des utilisateurs par JSON Web Token (JWT)
- Protection des fonctionnalités de l'application

### Gestion des applications
- Ajout et modification des applications supervisées
- Activation et désactivation des applications
- Gestion centralisée des informations des applications

### Gestion des interruptions
- Création, modification et suppression des natures d'interruption
- Protection contre la suppression des natures d'interruption déjà utilisées
- Enregistrement et suivi des périodes d'indisponibilité
- Consultation de l'historique des interruptions

### Tableau de bord de disponibilité
- Calcul des taux de disponibilité à partir des interruptions enregistrées
- Affichage de la disponibilité globale du système
- Visualisation des indicateurs clés de performance (KPI)
- Suivi de la fiabilité et aide au reporting opérationnel

### Interface responsive
- Interface adaptée aux ordinateurs, tablettes et smartphones
- Navigation et composants interactifs développés avec React

## Technologies utilisées

| Couche | Technologies |
|---|---|
| Frontend | React 18, React Router DOM, Axios, CSS |
| Backend | Node.js, Express.js |
| Base de données | PostgreSQL, node-postgres (pg) |
| Authentification | JSON Web Tokens (JWT) |
| API | API REST |

## Architecture de l'application

ERPWatcher repose sur une architecture client-serveur séparant les responsabilités du frontend, du backend et de la base de données.

**Frontend — React**

Interface utilisateur permettant de gérer les applications, d'enregistrer les interruptions et de consulter les indicateurs de disponibilité.

**Backend — Node.js / Express**

Expose les API REST, gère l'authentification, traite les données des applications et des interruptions et applique les règles métier.

**Base de données — PostgreSQL**

Stocke les informations des applications, les natures d'interruption, les périodes d'indisponibilité et les données associées.

### Flux de données

`Frontend React → API REST (Express) → PostgreSQL`

Le backend traite les requêtes, consulte ou modifie les données, puis renvoie les réponses à l'interface React.

## Captures d'écran

### Tableau de bord de disponibilité

![Tableau de bord ERPWatcher](screenshots/dashboard.png)

### Gestion des applications

![Gestion des applications](screenshots/applications.png)

### Suivi des interruptions

![Suivi des interruptions](screenshots/interruptions.png)

*Les captures d'écran doivent contenir uniquement des données de démonstration.*

## Points techniques

- Développement d'une application Full Stack avec React, Express et PostgreSQL.
- Mise en place d'une authentification JWT.
- Conception d'API REST pour la gestion des applications et des interruptions.
- Implémentation de règles métier empêchant la suppression de natures d'interruption déjà utilisées.
- Calcul des taux de disponibilité à partir des périodes d'indisponibilité.
- Développement d'interfaces responsive pour la supervision des applications.

## État du projet

**Projet personnel Full Stack**

Cette application démontre mes compétences pratiques en développement Full Stack à travers un processus complet de supervision des applications.

## Code source

Le code source complet est conservé dans un dépôt GitHub privé.

Ce dépôt public présente les fonctionnalités, l'architecture technique et les interfaces de l'application sans exposer son implémentation.

## Développeuse

**Carmela Urbano — Développeuse Full Stack**

- Portfolio : https://www.curbano.fr
- GitHub : https://github.com/carmela0505
