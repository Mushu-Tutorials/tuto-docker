# Tutoriel Docker

- [Installation](#installation "Installation")
- [Commandes Docker](# "Commandes Docker")
- [Les attributs](# "Les attributs")
- [Test de Docker](# "Test de Docker")
- []()

## Installation

Installer Docker en fonction de l'OS : [Docker Installer](https://www.docker.com/get-started "Docker Installer")
[Documentation Docker](https://docs.docker.com/ "Documentation Docker")

## Commandes Docker

- Version et info de Docker : `docker -v`, `docker version` et `docker info`
- Aide sur les commandes tapées : `docker MaCommandeDocker --help`
- Chercher l'image du container souhaité sur [DockerHub](https://hub.docker.com/ "DockerHub") ou via la commande `docker search MonContainer`
- Télécharger l'image d'un container : `docker pull mon_container`
- Lister les images des containers téléchargés : `docker images` [-a pour lister toutes les images]
- Lancer le container souhaité et les paramètres associés : `docker run mon_container -p 3300 -q mon_qarametre`
  - Liste des parametres possibles :
    - port : -p
    - azerty
- Lister les images téléchargées : `docker image ls` [--all ]
- Lister les containers qui sont actuellement lancés : `docker ps`
- Utiliser le container : `docker exec mon_container`

## Les attributs

- `-i`
- `-t`
- ``

## Test de Docker

- Lancer la commande `docker run hello-world` pour tester l'installation de docker.
```shell
docker run hello-world

Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
ca4f61b1923c: Pull complete
Digest: sha256:ca0eeb6fb05351dfc8759c20733c91def84cb8007aa89a5bf606bc8b315b9fc7
Status: Downloaded newer image for hello-world:latest

Hello from Docker!
This message shows that your installation appears to be working correctly.
...
```
