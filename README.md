# Pet Shop – Backend 🐾

## 📌 Description

This is the backend part of a pet store e-commerce project.  
It provides a REST API for managing categories, products, orders, and sales.

---

## 🗂 Project Structure
/database
/models
category.js      # Category model
product.js       # Product model
database.js        # Database connection setup
/public
/category_img       # Category images
/product_img        # Product images
/routes
categories.js       # Routes for categories
order.js            # Routes for orders
products.js         # Routes for products
sale.js             # Routes for sales
index.js              # Main server file
database.sqlite       # SQLite database file
package.json          # Project dependencies
package-lock.json
README.md             # Project description


## ⚙️ Installation and Running

1. Clone the repository:

```bash
git clone <repository URL>
cd <project folder>
npm install
npm run dev
The server will run on port 3333.


## API Testing
You can test the API using Postman, Axios, or any HTTP client.

🛠 Technologies Used
 • Node.js
 • Express
 • Sequelize
 • SQLite
 • Cors
 • Axios
