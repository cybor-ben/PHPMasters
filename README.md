# 📄 PHPMasters - Système de Facturation

Ce projet est une application de gestion de facturation développée avec une architecture robuste, visant à offrir une solution complète pour la gestion des données, des rapports et de l'authentification.

## 📁 Arborescence du Projet

```text

Facturation
├── assets
│   ├── css
│   │   └── styles.css
│   ├── images
│   │   ├── billets-dargent.png
│   │   └── facture-dachat.png
│   └── js
│       └── scanner.js
├── auth
│   ├── login.php
│   └── session.php
├── config
│   └── config.php
├── data
│   ├── factures.json
│   ├── produits.json
│   └── utilisateurs.json
├── docs
│   └── TP_PROGRAMMATION_WEB_PHP_L2_FASI_20252026-1.pdf
├── includes
│   ├── fonction-auth.php
│   ├── fonction-factures.php
│   ├── fonction-produits.php
│   ├── footer.php
│   └── header.php
├── modules
│   ├── admin
│   │   ├── gestion-comptes.php
│   │   └── suprimer-compte.php
│   ├── facturation
│   │   ├── afficher-facture.php
│   │   ├── calcul.php
│   │   └── nouvelle-facture.php
│   └── produits
│       ├── enregistrer.php
│       ├── lire.php
│       └── liste.php
├── rapports
│   ├── rapport-journalier.php
│   └── rapport-mensuel.php
├── .editorconfig
├── index.php
└── README.md

```

## 🧱 Structure du Projet

L'organisation des fichiers respecte une séparation stricte des responsabilités pour faciliter la maintenance :

- **assets/** :Ressources statiques (CSS, JavaScript)
- **auth/** : Gestion de l’authentification et des sessions
- **config/** : Paramètres globaux (taux TVA, chemins des fichiers, etc.)
- **data/** : Fichiers de persistance des données
- **docs/** : Documentation technique.
- **includes/** : Fonctions PHP réutilisables incluses dans les pages
- **modules/** : Modules fonctionnels (produits, facturation, administration)
- **rapports/** : Génération des rapports journaliers et mensuels
- **index.php** : Point d'entrée principal de l'application.

## 🛠️ Stack Technique

- **Backend** : PHP 
- **Frontend** : HTML5, CSS3, JavaScript
- **Base de données** : JSON
- **Outils** : Git, VS Code

---

## 🔧 Guide du Collaborateur (Workflow)

Pour assurer la stabilité de la branche principale (`main`), tous les collaborateurs doivent suivre ce workflow basé sur le **Forking**.

### 🚀 1. Initialisation

1.  **Forker** le projet sur GitHub (créer votre propre copie).
2.  **Cloner** votre fork localement :
    ```bash
    git clone [https://github.com/VOTRE_NOM/PHPMasters.git](https://github.com/VOTRE_NOM/PHPMasters.git)
    ```
3.  **Lier** le dépôt original (origin) :
    ```bash
    git remote add origin [https://github.com/cybor-ben/PHPMasters.git](https://github.com/cybor-ben/PHPMasters.git)
    ```

### 🔄 2. Cycle de Travail Quotidien

Avant de commencer toute modification :

1.  **Synchronisez-vous** avec le chef de projet :
    ```bash
    git checkout main
    git pull upstream main
    ```
2.  **Créez une branche** dédiée à votre tâche :
    ```bash
    git checkout -b feature/nom-de-la-tache
    ```
3.  **Codez et Commitez** vos changements :
    ```bash
    git add .
    git commit -m "Description claire de la modification"
    ```

### 📤 3. Soumission du travail

1.  **Poussez** la branche sur votre fork :
    ```bash
    git push origin feature/nom-de-la-tache
    ```
2.  **Ouvrez une Pull Request (PR)** sur GitHub vers le dépôt `cybor-ben/PHPMasters`.
3.  **Attendez la validation** : Le chef de projet (Admin) examinera votre code avant de fusionner.

---

## 🛡️ Rôle de l'Administrateur

- **Validation** : Seul l'admin approuve et fusionne les Pull Requests.
- **Protection** : La branche `main` est protégée contre les push directs pour éviter les erreurs.

---

© 2026 PHPMasters - Projet collaboratif de gestion.
