# My Awesome Project

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub stars](https://img.shields.io/github/stars/YourUsername/YourRepository.svg?style=social)](https://github.com/YourUsername/YourRepository/stargazers)

Welcome to my awesome project! This project does amazing things and you're going to love it.

## Features

- simple rest api with flask


## Installation

To install and run this project, follow these steps:

1. Build  the Docker container:

```bash
docker build -t flask-app .
```

2.  run the Docker container:

```bash
docker run -d -p 80:80 flask-app  

```
# Lister tous les conteneurs
docker ps

# Lister tous les conteneurs avec différents statuts
docker ps --all

# Lister les images
docker images

# Lister les images avec différents statuts
docker images --all

# Pull d'une image depuis le registre Docker
docker pull nginx

# Construire une image Docker
docker build -t python:3.9-slim

# Exécuter une image Docker
docker run python:3.9-slim

# Exécuter une image Docker avec le port exposé
docker run -d -p 80:80 flask-app   

# Arrêter un conteneur
docker stop id_conteneur

# Supprimer une image
docker rmi python:3.9-slim

# Supprimer un conteneur
docker rm 094514c7b74f8c6a899495d3ec10f43e68cfcb0c0181b568a6398cfeee80c3f3

# Git
# Ajouter tous les fichiers
git add -A

# Valider les modifications
git commit -m 'Evaluation'

# Créer une nouvelle branche
git branch dev

# Basculer vers la nouvelle branche
git checkout dev

# Pousser les modifications vers le dépôt distant
git push origin dev

# Récupérer les dernières modifications du dépôt distant
git pull origin dev

# Cloner le projet depuis GitHub
git clone https://github.com/raezon/flask-app
