---
title: S01 – SAS 
layout: home
---

**📅 S12 – PHP : Formulaires & navigation**

- **Période** : du **9 au 20 mars 2026** – *Semaines 10–11*
- **Thématique** : **Interaction utilisateur via formulaires et sessions**
- **Jour férié / vacances** : ✅ **Vacances de printemps** prévues du **21 au 28 mars 2026**

---

### 🧭 Objectifs de la session

* Apprendre à **traiter des formulaires HTML** avec PHP (`GET`, `POST`).
* Gérer la **navigation entre pages dynamiques** et transmettre des données entre scripts.
* Utiliser les **sessions et cookies** pour mémoriser des informations côté serveur.
* Réaliser un espace utilisateur très simple avec **affichage conditionnel**.

> 🔐 Cette session donne aux apprenants les **bases de la gestion d’état côté serveur**, nécessaires pour créer des sites personnalisés et interactifs.

---

### 📚 Unités d’apprentissage mobilisées

* **UA 7.2.1 – Formulaires HTML en PHP** – (3h) – référentiel
* **UA 7.2.2 – Sessions et cookies** – (3h) – référentiel

---

### 🧩 Prototype

**Titre** : *Formulaire de contact avec traitement PHP*

**Description** :
Créer une page avec un **formulaire HTML** (`nom`, `email`, `message`) traité via un fichier PHP :

* Validation simple (champs obligatoires)
* Affichage du message de confirmation ou d'erreur
* Affichage conditionnel du formulaire selon succès ou échec

Aucune base de données, uniquement des échanges `POST`.

---

### 🧪 Mini-Projet

**Titre** : *Espace utilisateur simplifié (sans base de données)*

**Description** :
Développer une mini-application PHP avec les fonctionnalités suivantes :

* Page de **connexion** (pseudo sans mot de passe)
* Stockage de l’identité utilisateur dans une **session PHP**
* Accès conditionnel à une page “Bienvenue” si l’utilisateur est connecté
* Possibilité de **se déconnecter** (suppression de session)

**Contraintes techniques** :

* Code en PHP procédural
* Pas de base de données
* Navigation entre plusieurs fichiers PHP
* Optionnel : utilisation de `$_COOKIE` pour mémoriser le pseudo

**Livrables attendus** :

* `login.php`, `bienvenue.php`, `logout.php`, `README.md`
* Dépôt GitHub conseillé

---

### 📊 Grille d’évaluation par niveau

* **Niveau 1** : Formulaire traité correctement, affichage de message simple
* **Niveau 2** : Gestion de session fonctionnelle, navigation entre pages
* **Niveau 3** : Application fluide, sécurisée, bien organisée avec logique conditionnelle
