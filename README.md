# Projet Angular pour la Surveillance des Battements de Cœur

Ce projet consiste en une application Angular qui communique avec une montre connectée pour afficher les graphiques des battements de cœur. L'application comprend deux interfaces distinctes : une interface administrateur et une interface client.

## Fonctionnalités

- Interface administrateur :
  - Ajout de clients
  - Gestion des données de battements de cœur
  - Suppression de clients
  - Supervision du système

- Interface client :
  - Consultation des données de battements de cœur
  - Suivi de l'évolution des données de battements de cœur

L'objectif principal de l'application est de permettre aux utilisateurs de surveiller leur santé cardiaque, de détecter d'éventuelles anomalies et de prendre des mesures appropriées.

## Technologie et Outils Utilisés

- **Angular**: Framework open-source de développement d'applications web.
- **TypeScript**: Langage de programmation utilisé avec Angular.
- **Angular-Highcharts**: Bibliothèque pour créer des graphiques interactifs dans des applications Angular.
- **UML (Unified Modeling Language)**: Langage de modélisation graphique utilisé pour concevoir le système.
- **Postman**: Outil de développement d'API pour tester et déboguer les API.
- **Git et GitHub**: Système de contrôle de version et plateforme de collaboration pour le développement de logiciels.
- **Java J2EE**: Plateforme de développement backend pour la création d'applications d'entreprise.

## Architecture

L'architecture de l'application repose sur le framework Angular, avec une approche basée sur les composants. Les composants principaux incluent :

- **ClientsComponent**: Gestion des clients, y compris l'ajout et la suppression de clients. Affiche une liste de clients et permet la recherche par nom.

- **DetailsComponent**: Affiche les détails d'un client spécifique, y compris ses données de battements de cœur.

- **GrapheComponent**: Affiche les graphiques de battements de cœur à partir des données du client.

- **LoginComponent**: Gère l'authentification des utilisateurs et les redirige en fonction de leur rôle (administrateur ou client).

- **NavbarComponent**: Affiche la barre de navigation de l'application.

La communication entre les composants et les services se fait via des appels HTTP vers le serveur backend, qui fournit les données des clients et des battements de cœur. Les services encapsulent la logique métier pour la récupération, la manipulation et la persistance des données.
