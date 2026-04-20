# 📄 PHPMasters - Système de Facturation

Ce projet est une application de gestion de facturation développée avec une architecture robuste, visant à offrir une solution complète pour la gestion des données, des rapports et de l'authentification.

## 📁 Arborescence du Projet

```text
facturation/
├── assets/             # Ressources statiques (CSS, JS, Images)
│   └── css/
│       └── styles.css
├── auth/               # Gestion des sessions et connexion
├── config/             # Configuration DB et constantes
├── data/               # Scripts SQL et exports de données
├── docs/               # Documentation technique (MCD, MLD, MPD)
├── includes/           # Composants UI réutilisables
│   ├── header.php
│   └── footer.php
├── modules/            # Logique métier (Factures, Clients, etc.)
├── rapports/           # Génération de statistiques et PDF
├── index.php           # Point d'entrée de l'application
└── README.md           # Documentation du projet
```

## 🧱 Structure du Projet

L'organisation des fichiers respecte une séparation stricte des responsabilités pour faciliter la maintenance :

- **assets/** : Ressources statiques (CSS, JS, images).
- **auth/** : Gestion de l'authentification et des sessions.
- **config/** : Fichiers de configuration (Base de données, variables d'environnement).
- **data/** : Stockage des données ou scripts SQL.
- **docs/** : Documentation technique et modèles (MCD, MLD).
- **includes/** : Composants réutilisables (header, footer, navbar).
- **modules/** : Logique métier par fonctionnalité.
- **rapports/** : Génération de documents et statistiques.
- **index.php** : Point d'entrée principal de l'application.

## 🛠️ Stack Technique

- **Backend** : PHP (Architecture modulaire)
- **Frontend** : HTML5, CSS3, JavaScript
- **Base de données** : MySQL
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
