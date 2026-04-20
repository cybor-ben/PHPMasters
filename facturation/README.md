# Structure Du Projet

facturation
 ┣ assets
 ┃ ┣ css
 ┃ ┃ ┗ styles.css
 ┃ ┗ js
 ┃ ┃ ┗ scanner.js
 ┣ auth
 ┃ ┣ login.php
 ┃ ┣ logout.php
 ┃ ┗ session.php
 ┣ config
 ┃ ┗ config.php
 ┣ data
 ┃ ┣ factures.json
 ┃ ┣ produits.json
 ┃ ┗ utilisateurs.json
 ┣ docs
 ┃ ┗ TP_PROGRAMMATION_WEB_PHP_L2_FASI_20252026-1.pdf
 ┣ includes
 ┃ ┣ fonction-auth.php
 ┃ ┣ fonction-factures.php
 ┃ ┣ fonction-produits.php
 ┃ ┣ footer.php
 ┃ ┗ header.php
 ┣ modules
 ┃ ┣ admin
 ┃ ┃ ┣ ajouter-compte.php
 ┃ ┃ ┣ gestion-comptes.php
 ┃ ┃ ┗ suprimer-compte.php
 ┃ ┣ facturation
 ┃ ┃ ┣ afficher-facture.php
 ┃ ┃ ┣ calcul.php
 ┃ ┃ ┗ nouvelle-facture.php
 ┃ ┗ produits
 ┃ ┃ ┣ enregistrer.php
 ┃ ┃ ┣ lire.php
 ┃ ┃ ┗ liste.php
 ┣ rapports
 ┃ ┣ rapport-journalier.php
 ┃ ┗ rapport-mensuel.php
 ┣ .editorconfig
 ┣ index.php
 ┗ README.md

# Points Essentiels Du projet

config/ # Paramètres globaux (Taux TVA, Chemins des fichiers, etc)

auth/ # Gestions de l'authentification et des sessions

modules/ # Modules Fonctionnels du projet

data/ # Fichiers de persistance des données

includes/ # Fonctions PHP réutilisables incluse dans les pages

assets/ # Ressources Statiques CSS,JAVASCRIPT

rapports/ # Géneration des rapports journaliers et mensuels

docs/ # Fichier Source du tp

.editorconfig/ # Fichier de configuration de l'editeur

# Guide d'installation 

PHP serveur local:
  php -S localhost:8000
  Télechargement:
    https://www.php.net/downloads.php

Xampp serveur:
  https://www.youtube.com/watch?v=cKgs4xfpE9w
  Télechargement:
    https://www.apachefriends.org/download.html

Laragon serveur:
  https://www.youtube.com/watch?v=sHHl5kihXD4
  Télechargement:
    https://laragon.org/download


# Documentation Bootstrap

https://getbootstrap.com/


# Git Workflow

