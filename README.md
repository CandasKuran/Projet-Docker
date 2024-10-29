# Projet-Docker

## Description
Ce projet configure un environnement WordPress avec Docker Compose, incluant Nginx, WordPress et MySQL.

## Contenu
- **Fichier Docker Compose** : `docker-compose.yml`
- **Configuration Nginx** : `app/nginx/default.conf`
- **Fichiers WordPress et autres** : dossier `wordpress`

## Installation
1. Assurez-vous que Docker et Docker Compose sont installés.
2. Démarrez l’environnement avec la commande : `docker-compose up -d`.

## Accès à Nginx et à la Base de Données
- **Nginx** : Accédez via `localhost:8081`.
- **Base de Données (HeidiSQL)** :
  - **Nom de l'hôte** : `localhost`.
  - **Nom de la base de données** : `exampledb`.
  - **Utilisateur** : `admin`.
  - **Mot de passe** : `admin`.
  - **Mot de passe root** : `rootpassword`.

