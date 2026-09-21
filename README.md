# Projet AP7 — Application d'Attribution des Places de Parking

Ce projet consiste à développer une application web de réservation et d'attribution de places de parking numérotées pour le personnel des ligues afin d'éviter le stationnement sauvage.

---

## 📌 Livrables — Itération 1 (Documentation)

### 1. Plan du site & Structure des URLs

#### 🟢 Espace Public & Authentification
* `/login` : Page de connexion
* `/register` : Inscription du personnel
* `/forgot-password` : Mot de passe oublié

#### 🔵 Espace Utilisateur (Front-Office)
* `/dashboard` : Tableau de bord (place attribuée, rang sur la file d'attente, actions)
* `/history` : Historique des réservations passées
* `/profile` : Modification des informations personnelles
* `/logout` : Déconnexion

#### 🔴 Espace Administrateur (Back-Office)
* `/admin/dashboard` : Vue d'ensemble du parking
* `/admin/users` : Gestion et validation des comptes utilisateurs
* `/admin/parking-spots` : Gestion de la liste des places de parking
* `/admin/queue` : Gestion de la file d'attente et réattribution manuelle

---

### 2. Modèle Conceptuel de Données (MCD)

Le MCD modélise la structure de la base de données (Utilisateurs, Places, Réservations, File d'attente).

---

### 3. Maquettes de l'application

Les maquettes illustrent les interfaces du front-office utilisateur et du back-office administrateur :

* [Voir la maquette - Connexion / Inscription](maquette-login.png)
* [Voir la maquette - Tableau de bord Utilisateur](maquette-dashboard.png)
* [Voir la maquette - Administration](maquette-admin.png)
