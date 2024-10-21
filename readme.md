# Nginx Web Server with Custom App

## Description

Ce dépôt contient les fichiers nécessaires pour exécuter un serveur web Nginx avec une application personnalisée située dans le dossier `app1`. 



Le serveur Nginx écoutera sur le port `8092` et servira le contenu du dossier `app1` situé dans le répertoire racine du dépôt.

## Structure du dépôt


| Dossier/File         | Description                                           |
|------------------------|-------------------------------------------------------|
| ├── app1/              | `Dossier contenant votre application web (HTML, CSS, JS, etc.)`  |
| ├── docker-compose.yml |  `Fichier docker-compose pour exécuter le conteneur Nginx` |
| └── README.md          | `Le fichier README de votre projet`                     |




## Prérequis

Avant de commencer, assurez-vous d'avoir installé les logiciels suivants sur votre machine :
- [Docker](https://www.docker.com/get-started)
- [Docker Compose](https://docs.docker.com/compose/install/) (si vous optez pour la méthode `docker-compose`)


## Lancement du service web
```bash
# Clonez ce dépôt en utilisant la commande suivante :
> git clone https://github.com/votre-utilisateur/votre-repo.git
> cd votre-repo

# Assurez-vous que vous êtes dans le répertoire racine du dépôt cloné, où se trouve le fichier docker-compose.yml. Exécutez la commande suivante pour démarrer le serveur Nginx :
> docker-compose up -d
```

## Objectifs 
- Créer deux branches, `branche-ghibli` et `branche-tmdb`
- Réaliser l'activité des `studios Ghibli` dans `branche-ghibli` , à chaque étape d'avancement, réaliser les commits nécessaires au suivi de version.
- Concevoir la diapo d'explications du tutoriel des studios Ghibli dont vous ajouterez le lien dans votre fichier `readme.md` (le lien pointera sur un google slide dont tous les utilisateurs du lien auront des droits de lecture) 
- Répondre au QCM
- Réaliser l'activité sur `TMDB` dans la `branche-tmdb`, à chaque étapes d'avancement réaliser les commits nécessaires au suivi de version.

Vous devrez expliquer si vous y êtes invité à l'oral, comment fusionner les différentes branches sur la branche principale afin de livrer l'application.

## Cahier des charges et ressources de l'activité 
Le [Slide de l'activité](https://docs.google.com/presentation/d/1_PhEzmjdi0lf7SBHLvpWLcyYPGcEl9zfxtRIv6gruEE/edit?usp=sharing) intégre les liens des différents ressources.


## Notation
- Compréhension du tutoriel Ghibli et commits avec des messages claires montrant leurs intérêts
- QCM
- TMDB, code maîtrisé de bout en bout
- Evaluation Orale du Slide

# Présentation Orale
[Mon Google Slide ](#)

