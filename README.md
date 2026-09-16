# 🇵🇸 PalRoots – Palestinian Products Marketplace

PalRoots is a full-stack e-commerce marketplace designed to connect customers with sellers of Palestinian products through a modern, responsive web application.

The platform provides separate experiences for **buyers, sellers, and administrators**, allowing users to browse products, manage shopping carts, place orders, save favorites, submit ratings, and manage products and orders.

---

## 🚀 Project Overview

PalRoots was developed as a graduation project to demonstrate practical full-stack web development skills, including frontend development, backend API development, database management, authentication, and role-based access control.

The application follows a client-server architecture:

- **Frontend:** React-based web application
- **Backend:** Flask REST API
- **Database:** MySQL
- **Authentication:** JWT
- **API Communication:** REST APIs

---

## ✨ Features

### 👤 Buyer Features

- User registration and login
- Browse available products
- View product details
- Search and browse products by category
- Add products to cart
- Update cart quantities
- Place orders
- View order history
- Add products to favorites
- Rate products
- Responsive user interface

### 🏪 Seller Features

- Seller registration and authentication
- Seller dashboard
- Add new products
- Update products
- Delete products
- Manage product information
- View and manage orders related to their products

### 🛠️ Admin Features

- Secure administrator authentication
- Admin dashboard
- Manage users
- Manage sellers
- Manage products
- Manage categories
- Manage orders
- Monitor marketplace data

---

## 🔐 Authentication & Security

The application uses **JWT (JSON Web Token) authentication** to protect user accounts and restricted API endpoints.

Role-based access control is implemented for:

- Buyers
- Sellers
- Administrators

Protected routes ensure that users can only access functionality allowed for their role.

---

## 🧰 Technologies Used

### Frontend

- React
- JavaScript
- TypeScript
- HTML5
- CSS3
- Bootstrap
- Responsive Web Design

### Backend

- Python
- Flask
- Flask REST APIs
- JWT Authentication
- SQLAlchemy

### Database

- MySQL
- SQL

### Development Tools

- Git
- GitHub
- Visual Studio Code
- Vite

---

## 🏗️ Project Structure

```text
PalRoots-Marketplace/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── index.html
│   ├── package.json
│   ├── package-lock.json
│   ├── vite.config.js
│   └── .env.example
│
├── backend/
│   ├── app/
│   ├── run.py
│   ├── requirements.txt
│   ├── setup_data.py
│   ├── create_admin.py
│   ├── reset_db.py
│   ├── alter.py
│   └── .env.example
│
└── README.md
