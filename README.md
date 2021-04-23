# multistream

## Documentations

NGINX-RTMP-DOCKER : https://github.com/tiangolo/nginx-rtmp-docker/blob/master/Dockerfile
NGINX-RTMP-MODULE : https://github.com/arut/nginx-rtmp-module/

## Installation

### Configuration du serveur OVH

Creation d'une instance Public Cloud sur OVH : B2-7 (7 Go RAM, 2 vCores (2,3 GHz), 50 Go SSD, 250 Mbit/s)
Localisation : Gravelines GRA3
Sélectionnez une image : Ubuntu 20.04
Clé SSH : ssh_key_4096
Nombre d'instances à créer : 1
Nom de l'instance : b2-7-gra3-multistream
Script de post-installation :
    #!/bin/bash

    echo "test" >> test.txt
Sauvegarde automatisée des instances : Oui
Sélectionnez une période de facturation : Horaire

### Lancer le script d'installation

