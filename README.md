# C-DevSecOps-B3-DEV-B-eval-pratique

Voici notre guide pour setup notre projet DevSecOps :

- Cloner le repository avec le docker-compose.yml qui permettra la configuration des containers docker.

- Mettez vous dans le dossier que vous vennez de clone avec la commande 'cd'

- Dans une VM Ubuntu, lancez la commander 'docker-compose up -d'.

- Dirigez vous dans votre fichier 'hosts' de votre Windows souvent sur ce chemin d'accès la : 
'C/Windows/System32/drivers/etc/hosts'
Vous pouvez rajouter l'adresse suivante : 'www.numeration.com:8000'
(Le port 8000 correspond au port dans le docker-compose.yml allouer pour notre Wordpress)

- Allez sur un navigateur Web et tapez l'url juste au dessus, vous devriez voir apparaitre la page d'accueil de Wordpress !

Félicitations !
