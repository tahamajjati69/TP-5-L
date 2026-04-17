# 🏛️ Projet : Système de Gestion de Bibliothèque (v1.0)

**Développement Full-Stack | Node.js • Express • PostgreSQL • EJS**
---
## 🏗️ Architecture du projet

```
bibliotheque-app/
├── config/
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── .env
├── app.js
└── package.json
```


---

## 📝 Présentation du TP
Ce projet consiste en la création d'une plateforme de gestion bibliothécaire dynamique. L'objectif est de manipuler des données complexes (Auteurs et Livres) tout en respectant une architecture logicielle robuste et une interface utilisateur moderne.

### 🚀 Stack Technique
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![EJS](https://img.shields.io/badge/EJS-A91E50?style=for-the-badge&logo=ejs&logoColor=white)

---

## 🏗️ Structure de l'Application (Modèle MVC)

Le projet est organisé de manière modulaire pour séparer les responsabilités :

* **`app.js`** : Point d'entrée de l'application et configuration des middlewares.
* **`/config`** : Gestion de la connectivité avec l'instance PostgreSQL.
* **`/models`** : Logique d'accès aux données (Requêtes SQL brutes).
* **`/controllers`** : Traitement de la logique métier et rendu des vues.
* **`/routes`** : Définition des points d'accès (Endpoints) de l'API.
* **`/public`** : Ressources statiques (Design CSS Émeraude & Scripts Client).
* **`/views`** : Interfaces dynamiques conçues avec EJS.

---

## 🛠️ Installation & Configuration

### 1. Préparation de l'environnement
```bash
# Initialisation du dossier
mkdir bibliotheque-taha && cd bibliotheque-taha

# Installation des modules essentiels
npm install express ejs pg dotenv
npm install --save-dev nodemon
```

## 📌 Fonctionnalités

### 👤 Auteurs

* ➕ Ajouter un auteur
* 📋 Afficher la liste
* 🔍 Voir les détails
* ✏️ Modifier
* ❌ Supprimer

---

### 📖 Livres

* ➕ Ajouter un livre
* 📋 Afficher la liste
* 🔍 Voir les détails
* ✏️ Modifier
* ❌ Supprimer
* 🔎 Recherche par titre, auteur ou genre

---

## 🔗 Relation entre les tables

* Un **auteur** peut avoir plusieurs livres
* Un **livre** appartient à un seul auteur

👉 Relation : **One-to-Many**

---

## 🎨 Interface utilisateur

* Interface responsive (CSS personnalisé)
* Tableaux stylisés
* Formulaires modernes
* Badges de disponibilité
* Navigation simple et intuitive

  *Ajouter un Auteur:*
<img width="1806" height="637" alt="image" src="https://github.com/user-attachments/assets/de8f9f1c-67ff-4e59-84b3-f22d5fd7232c" />

*Affichage:*

<img width="1537" height="412" alt="image" src="https://github.com/user-attachments/assets/290fa649-1240-4818-9af6-ca228cee4f1d" />


*Details:*

<img width="1650" height="500" alt="image" src="https://github.com/user-attachments/assets/eaad0f7a-f861-4525-bc70-ed5942cf7464" />

  *Ajouter un Livre:*
  
<img width="1542" height="496" alt="image" src="https://github.com/user-attachments/assets/57b1527d-9c07-4d3b-9dc7-f2fb40418119" />

<img width="1801" height="532" alt="image" src="https://github.com/user-attachments/assets/322d6268-6ca1-40e9-b4dd-3ef489b9b3fc" />

---
## Video de demonstration :


https://github.com/user-attachments/assets/d34bf17b-9443-4e02-8704-165db811d857

---

---

## ⚠️ Gestion des erreurs

* Page 404 (route inexistante)
* Page erreur serveur (500)
* Vérification des données inexistantes

---

## 🧪 Tests

Tester les routes suivantes :

* `/` → Accueil
* `/auteurs` → Liste auteurs
* `/auteurs/ajouter`
* `/livres` → Liste livres
* `/livres/recherche?q=mot`





---

## 🔧 Améliorations possibles

* 🔐 Authentification (JWT / Passport)
* 📦 Gestion des emprunts
* 🖼️ Upload d’images de couverture
* 📊 Dashboard statistiques
* 📄 Pagination

---

## 📚 Technologies utilisées

* Node.js
* Express.js
* EJS
* PostgreSQL
* HTML / CSS / JavaScript

---

## ✅ Conclusion

Ce TP permet de comprendre :

* L’architecture MVC en Node.js
* L’intégration avec PostgreSQL
* La gestion des relations entre tables
* La création d’une application web complète

---

## 👨‍💻 Auteur
Nom : Majjati Mohamed Taha
Projet réalisé dans le cadre du cours :
**Développement Web Full-Stack avec JavaScript**
