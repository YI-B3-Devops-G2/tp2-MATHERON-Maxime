# tp2-MATHERON-Maxime
## Info
mail: maxime.matheron@ynov.com

github_username: bambin401

Professeur : [@aegirops](https://github.com/aegirops)

# Prérequis
- [Docker](https://hub.docker.com/?overlay=onboarding)
- git (pour [Windows](https://gitforwindows.org/))
- un shell (inclut avec [git bash](https://gitforwindows.org/) pour windows)

# Installation et démarrage
1) Cloner le dépôt
2) Exécuter la commande ``` docker-compose -f ./docker-compose.yaml up --build --force-recreate ```, patienter durant l'installation

# Utilisation

`localhost:3000` Page d'acceuil Nginx

`localhost:3000/api` Page  'hello world' de l'API 

`localhost:3000/api/status` Page l'API qui récupere le uptime de postgres et le nombre de clients connectés sur redis
