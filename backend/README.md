# GROUPOMANIA BACK END #

## Installation ##

Lancer `npm install`

Lancer serveur mysql (mamp par exemple) puis créer base de donnée `groupomania`

Configuration host, user/mdp dans config/db.config.js

---------------------------------------------

Enlever commentaire dans app.js lignee 77-78-79 pour la construction de la bdd (db.sequelize.sync)

!! ATTENTION !! Cela resync à chaque fois que le serveur démarre donc remise à zéro des données 

---------------------------------------------

## Usage ##

Lancer `node server` ou `nodemon server`

Port : 3001

Utiliser `Ctrl+C` dans le terminal pour arrêter le serveur local.


## SWAGGER ##

http://localhost:3001/api-docs/
=> swagger-output.json