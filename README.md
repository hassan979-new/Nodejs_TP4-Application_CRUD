# Node.js – CRUD Produits avec MySQL et Express

## 📖 Description
Ce projet est une **application Node.js** utilisant **Express.js**, **MySQL** et le moteur de templates **EJS** pour gérer un catalogue de produits.  
Il illustre la mise en place d’un CRUD complet (Create, Read, Update, Delete) avec une architecture MVC simplifiée, une base de données relationnelle et une interface utilisateur stylisée.

---

## 📂 Structure du projet
```
crud-app/
├── config/
│   └── db.js
├── controllers/
│   └── productController.js
├── models/
│   └── product.js
├── public/
│   └── css/
│       └── style.css
├── views/
│   ├── layout.ejs
│   ├── error.ejs
│   ├── partials/
│   │   ├── header.ejs
│   │   └── footer.ejs
│   └── products/
│       ├── index.ejs
│       ├── details.ejs
│       ├── create.ejs
│       └── edit.ejs
├── app.js
├── .env
└── package.json
```

---

## ⚙️ Fonctionnalités

### Base de données MySQL
- Connexion via **mysql2/promise** avec pool de connexions.  
- Table `products` contenant `id`, `name`, `price`, `description`, `created_at`.  
- Requêtes SQL pour lecture, insertion, mise à jour et suppression.  

### Contrôleur Produits
- `getAllProducts` : liste tous les produits.  
- `getProductById` : affiche les détails d’un produit.  
- `showCreateForm` : formulaire d’ajout.  
- `createProduct` : ajoute un produit en base.  
- `showEditForm` : formulaire de modification.  
- `updateProduct` : met à jour un produit existant.  
- `deleteProduct` : supprime un produit.  

### Interface utilisateur
- Pages EJS avec layout commun (header/footer).  
- Liste des produits avec boutons d’édition et suppression.  
- Formulaires pour ajouter et modifier un produit.  
- Stylisation avec **Bootstrap-like CSS** et responsive design.  

### Gestion des erreurs
- Page `error.ejs` pour afficher les erreurs serveur ou produit non trouvé.  
- Middleware Express pour gérer les routes inexistantes et les exceptions.  

---

## 🖥️ Exemple d’exécution

https://github.com/user-attachments/assets/afee4169-7c27-4435-9d8c-88c531a64ddf

---

## 💡 Concepts pratiqués
- Connexion à une base MySQL avec **mysql2/promise**.  
- Architecture MVC (config, modèles, contrôleurs, vues).  
- Templates dynamiques avec **EJS** et layout global.  
- Gestion des formulaires et des routes avec Express.  
- Stylisation responsive avec CSS.  
- Validation et gestion des erreurs serveur.  

---

## 🧑‍💻 Auteur
- 👤 **Agouram Hassan**  
- ⚙️ Développement Node.js 
- 🎓 Instructor : **Mr. LACHGAR**  
- 📅 Mai 2026

