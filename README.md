# Projet SAE - Carmate
## Sommaire 
- [Comment lancer l'application ?](#comment-lancer-lapplication)
    - [Installer `docker` sur Linux (Debian)](#installer-docker-sur-linux-debian)
    - [Installer `docker` sur Windows](#installer-docker-sur-windows)
    - [Commande pour lancer l'application](#commande-pour-lancer-lapplication)
- [Repositories du projet](#repositories-du-projet)

## Comment lancer l'application ?
__Prérequis:__ 
- Avoir une connection internet
- Avoir `docker` sur votre PC

### Installer `docker` sur Linux (Debian)
```
sudo apt-get install docker-ce \
                     docker-ce-cli \
                     containerd.io \
                     docker-buildx-plugin \
                     docker-compose-plugin
```
### Installer `docker` sur Windows
Suivre ce lien : https://docs.docker.com/desktop/install/windows-install/

### Commande pour lancer l'application
Soyez en root ou administrateur sur votre pc et tapez cette commande :
```
docker compose up
```

### Commande pour lancer l'application sous la version de developpement
Soyez en root ou administrateur sur votre pc et tapez cette commande :
```
docker compose -f docker-compose.develop.yml up
```

## Repositories du projet
- Back : https://github.com/DUT-Info-Montreuil/SAE-5.A-carmate-back
- Front : https://github.com/DUT-Info-Montreuil/SAE-5.A-carmate-front
- Database : https://github.com/DUT-Info-Montreuil/SAE-5.A-carmate-database

## Développeurs sur le projet
- Tiago NARCISO
- Antoine BOUCHE
- Mathéo NGUYEN
- Ayman El Mechta
- Naulan CHRZASZCZ
