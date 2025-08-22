# Utilisation de Docker avec Node.js

Ce projet utilise Docker pour faciliter le déploiement et l'exécution de l'application Node.js.

## Fichiers importants

- `Dockerfile` : Définit l'image Docker de l'application.
- `compose.yml` : Définit les services et la configuration multi-conteneurs avec Docker Compose.

## Commandes pour exécuter les fichiers

### 1. Construire l'image Docker

```
docker build -t nom-image .
```

Remplacez `nom-image` par le nom que vous souhaitez donner à votre image Docker.

### 2. Lancer les services avec Docker Compose

```
docker compose up
```

Pour exécuter en arrière-plan (détaché) :

```
docker compose up -d
```

### 3. Arrêter les services

```
docker compose down
```

## Prérequis

- [Docker](https://www.docker.com/) et [Docker Compose](https://docs.docker.com/compose/) installés sur votre machine.

## Références

- [Documentation Docker](https://docs.docker.com/)
- [Documentation Docker Compose](https://docs.docker.com/compose/)
# app-web-nodejs-docker-img
