# 📦 TP 4 : Application CRUD avec MySQL, EJS et Express.js
Cours : Développement web full-stack avec JavaScript

## 📌 Description

Ce projet est une application web CRUD permettant de gérer des produits (ajouter, afficher, modifier, supprimer)
en utilisant **Node.js**, **Express**, **MySQL** et **EJS**.

---

## ⚙️ Technologies utilisées

* Node.js
* Express.js
* MySQL
* EJS (template engine)
* Bootstrap (design)

---

## 🔄 Fonctionnalités (CRUD)

* ➕ Ajouter un produit
* 📄 Afficher la liste des produits
* 🔍 Voir les détails d’un produit
* ✏️ Modifier un produit
* ❌ Supprimer un produit

---

## 📁 Structure du projet

```
crud-express-mysql/
│── controllers/
│── models/
│── views/
│   ├── partials/
│   ├── products/
│── public/
│   └── css/
│── config/
│── app.js
│── package.json
│── .env
```

---

## 🛠️ Installation

```bash
# Cloner ou créer le projet
npm init -y

# Installer les dépendances
npm install express mysql2 ejs body-parser dotenv express-ejs-layouts
```

---

## ⚙️ Configuration

Créer un fichier `.env` :

```
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=
DB_NAME=crud_app
PORT=3000
```

---

## 🗄️ Base de données

```sql
CREATE DATABASE crud_app;
USE crud_app;

CREATE TABLE products (
  id INT AUTO_INCREMENT PRIMARY KEY,
  name VARCHAR(255),
  price DECIMAL(10,2),
  description TEXT,
  created_at TIMESTAMP DEFAULT CURRENT_TIMESTAMP
);
```

---

## ▶️ Lancer l’application

```bash
node app.js
```

Puis ouvrir :
👉 http://localhost:3000

---

## 📌 Architecture

* **Model** : gestion des données (MySQL)
* **Controller** : logique métier
* **View** : affichage avec EJS

---

## 🚀 Améliorations possibles

* Validation des formulaires
* Pagination
* Recherche et tri
* Authentification utilisateur
* Upload d’images
* API REST

---

## ✅ Conclusion

Ce projet permet de comprendre :

* le fonctionnement du CRUD
* l’architecture MVC
* la connexion entre Node.js et MySQL

---
## Resultat



https://github.com/user-attachments/assets/28c0582e-fe7b-4d75-b85c-6c9ba2ecf6b9

