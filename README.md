# admiralis

>⚠️ Ce projet est encore en cours de développement ! ⚠️

>⚠️ A ce jour, le front-end n'est pas encore inclus ! ⚠️

## Prérequis

- Docker

## Installation (backend uniquement)

- Cloner le répository : `git clone https://github.com/Admiralis/admiralis.git`
- Se placer à la racine : `cd admiralis`
- Lancer le reverse proxy : `docker-compose up`

## Front-end

Si vous souhaitez tester la partie front-end web de l'application : 
- `git clone https://github.com/Admiralis/front-ionic.git`
- `cd front-ionic`
- `npm install`
- `npm start`

Assurez-vous que le reverse proxy soit lancé.
L'ensemble de la stack sera accessible sur le port 80.
N'utilisez pas le port 3000 pour accéder au front ou vous n'aurez pas accès au backend !
