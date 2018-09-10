# Tutoriel Docker

## Installation

Installer Docker en fonction de l'OS : [Docker Installer](https://www.docker.com/get-started "Docker Installer")

## Commandes Docker

- Version de Docker : `docker -v`
- Télécharger l'image d'un container : `docker pull mon_container`
- Lister les images des containers téléchargés : `docker images` [-a pour lister toutes les images]
- Lancer le container souhaité et les paramètres associés : `docker run mon_container -p 3300 -q mon_qarametre`
  - Liste des parametres possibles :
    - port : -p
    - azerty
- Lister les containers qui sont actuellement lancés : `docker ps`
- Utiliser le container : `docker exec mon_container`
