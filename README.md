CatchChallenge
==============

A Symfony project created on December 14, 2016, 2:34 pm.

Pré-requis

Avoir "composer" d'installé ==> https://getcomposer.org/doc/00-intro.md
Initialisation du projet

    SSH git clone git@github.com:AF1890/CatchChallenge.git
    HTTPS git clone https://github.com/AF1890/CatchChallenge.git
    cd CatchChallenge
    composer install
    php app/console doctrine:database:create
    php app/console doctrine:schema:update --force
    php app/console asset:install
