# Projet Full Stack CI/CD

## Introduction

Ce projet illustre l'application des principes d'intégration continue (CI) et de déploiement continu (CD) à une application Full Stack développée avec Node.js et Express. Il vise à démontrer une mise en œuvre pratique des concepts étudiés en classe, tout en fournissant une base solide pour le déploiement d'applications modernes avec Docker.

## Architecture du Projet

Le projet est structuré autour des composants suivants :

- **Backend** : Construit avec Node.js et Express pour gérer la logique applicative et la communication avec la base de données.
- **API REST** : Fournit une interface pour les interactions entre le frontend et le backend.
- **Base de Données** : Stocke les informations nécessaires au fonctionnement de l'application.
- **Docker** : Utilisé pour containeriser l'application, assurant ainsi une portabilité et une consistence entre les environnements de développement et de production.

## Configuration CI/CD

Le projet intègre des pipelines CI/CD configurés pour automatiser les tests, les builds, et le déploiement de l'application. Ces configurations garantissent que chaque changement apporté au code est automatiquement testé et déployé, réduisant ainsi le risque d'erreurs et accélérant le processus de développement.

## Démarrage Rapide

Pour lancer l'application localement, suivez ces étapes :

1. Clonez le dépôt : `git clone https://github.com/OuchTech/cicd`
2. Construisez l'image Docker : `docker build -t cicdfullstack .`
3. Lancez le conteneur : `docker run -dp 3000:3000 cicdfullstack`

## Tests

Les tests unitaires peuvent être exécutés avec la commande suivante : `npm test`. Ces tests assurent la fiabilité des fonctionnalités de base de l'application.


