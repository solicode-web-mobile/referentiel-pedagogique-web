---
title: Blog - Intégration front/back
layout: home
nav_order: 16
---
# **📅 S16 – Blog : Intégration front/back**

- **Période** : du **18 au 29 mai 2026** – *Semaines 18–19*
- **Thématique** : **Relier formulaires et base de données – blog dynamique**
- **Jour férié / vacances** : Aucun

---

### 🧭 Objectifs de la session

* Connecter les **formulaires HTML** du blog à une base de données MySQL via PHP.
* Traiter les envois de données : **insertion, lecture, affichage dynamiques**.
* Sécuriser les interactions avec la base (requêtes préparées, validation).
* Simuler les premiers **articles dynamiques** en base (lecture + insertion).

> 🔗 Cette session est le **pont entre la structure front-end statique** et le **fonctionnement dynamique back-end** du blog.

---

### 📚 Unités d’apprentissage mobilisées

* **UA 6.1.3 – Sécuriser les requêtes SQL** – (4h) – référentiel
* **UA 7.2.1 – Formulaires HTML en PHP** – (3h) – référentiel
* **UA 7.2.2 – Sessions et cookies** – (3h) – référentiel

---

### 🧩 Prototype

**Titre** : *Formulaire de création d’article connecté à MySQL*

**Description** :
À partir de la structure HTML existante, intégrer un **formulaire PHP** permettant d’ajouter un article dans une base :

* champs : titre, contenu, auteur
* validation minimale
* insertion dans une table `posts`
* confirmation d’ajout

Connexion via PDO, avec requêtes préparées.

---

### 🧪 Mini-Projet

**Titre** : *Blog dynamique PHP/MySQL – version 1*

**Description** :
Faire évoluer le blog statique (développé en S15) vers une version **dynamique connectée** :

* Page d’accueil : affiche les articles depuis la base
* Page formulaire : ajoute un article dans la base
* Page article : affiche les détails d’un article par `id`
* Système de session simplifié : affichage d’un message de bienvenue si connecté

**Contraintes techniques** :

* PHP procédural avec PDO
* Sécurité basique (requêtes préparées, contrôle des champs)
* Navigation claire entre les pages

**Livrables attendus** :

* Arborescence du projet (`index.php`, `article.php`, `form.php`, `db.php`, etc.)
* Script SQL de la base
* Dépôt GitHub avec README

---

### 📊 Grille d’évaluation par niveau

* **Niveau 1** : Formulaire connecté, insertion en base fonctionnelle
* **Niveau 2** : Affichage dynamique des articles, navigation fluide
* **Niveau 3** : Sécurisation minimale, code structuré, réutilisable
