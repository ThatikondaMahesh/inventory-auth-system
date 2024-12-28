# 🛍️ Node.js Inventory Management System

## 📖 Overview
This project is a **Node.js-based Inventory Management System** designed to demonstrate the **MVC (Model-View-Controller)** architecture. It provides a comprehensive solution for administrators to manage products effectively, offering features such as adding, updating, and removing products, along with secure user registration and login functionalities. The project prioritizes modularity, scalability, and clean code structure.

---

## 🗂️ Project Structure

```
INVENTORY-MANAGEMENT-SYS
|-- 📂 node_modules/
|-- 📂 public/
|   |-- 📂 css/
|   |   |-- 📄 headers.css
|   |-- 📂 images/
|   |-- 📄 main.js
|-- 📂 src/
|   |-- 📂 controllers/
|   |   |-- 📄 product.controller.js
|   |   |-- 📄 user.controller.js
|   |-- 📂 middlewares/
|   |   |-- 📄 auth.middleware.js
|   |   |-- 📄 file-upload.middleware.js
|   |   |-- 📄 lastVisit.middleware.js
|   |   |-- 📄 validation.middleware.js
|   |-- 📂 models/
|   |   |-- 📄 product.model.js
|   |   |-- 📄 user.model.js
|   |-- 📂 views/
|       |-- 📄 index.ejs
|       |-- 📄 layout.ejs
|       |-- 📄 login.ejs
|       |-- 📄 new-product.ejs
|       |-- 📄 register.ejs
|       |-- 📄 update-product.ejs
|-- 📄 .gitignore
|-- 📄 index.js
|-- 📄 package-lock.json
|-- 📄 package.json
```

---

## ✨ Features

### 🛍️ Product Management
- ➕ Add, ✏️ edit, and ❌ remove products.
- View detailed inventory lists dynamically.

### 🔐 Secure User Authentication
- User registration and login with password validation.
- Authentication middleware to secure routes.

### 📋 Middleware Functionalities
- **auth.middleware.js**: Verifies user authentication and protects restricted routes.
- **validation.middleware.js**: Validates user inputs for registration and product operations.
- **file-upload.middleware.js**: Handles file uploads for product images.
- **lastVisit.middleware.js**: Tracks user activity timestamps.

### 🌐 Dynamic User Interface
- Built with **EJS** templates for responsive and interactive views.

---

## 🔧 Technologies Used
- **Node.js**: Backend runtime environment.
- **Express.js**: Web application framework for building RESTful APIs.
- **EJS**: Templating engine for rendering dynamic views.
---

## 🚀 Getting Started

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/ThatikondaMahesh/inventory-product-admin-system.git
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Configure MongoDB
- Update the database connection string in `index.js` with your MongoDB URI.

### 4️⃣ Run the Application
```bash
npm start
```

### 5️⃣ Access the Application
- Open your browser and visit: `http://localhost:3000`

---

## 📂 Folder Explanations

### **1. Public Folder**
Contains static assets like CSS, JavaScript, and images used in the views.

### **2. Controllers**
Handles business logic for routes:
- **product.controller.js**: Logic for product operations.
- **user.controller.js**: Logic for user registration and login.

### **3. Models**
Defines schemas:
- **product.model.js**: Schema for product data.
- **user.model.js**: Schema for user data.

### **4. Middlewares**
Custom middleware functions:
- **auth.middleware.js**: Protects routes requiring authentication.
- **validation.middleware.js**: Validates incoming requests.
- **file-upload.middleware.js**: Handles image uploads.
- **lastVisit.middleware.js**: Tracks user activity timestamps.

### **5. Views**
EJS templates for rendering pages dynamically:
- **index.ejs**: Homepage view.
- **login.ejs**: Login page.
- **register.ejs**: User registration page.
- **new-product.ejs**: Add a new product.
- **update-product.ejs**: Update product details.

---

## 🌐 API Endpoints

### 🔒 Authentication
- **POST** `/login`: User login.
- **POST** `/register`: User registration.

### 🛍️ Product Management
- **GET** `/products`: Fetch all products.
- **POST** `/products`: Add a new product.
- **PUT** `/products/:id`: Update product details.
- **DELETE** `/products/:id`: Delete a product.

---

## 🤝 Contributions
Contributions are welcome! Feel free to open issues or submit pull requests to enhance the project.

---

## 📜 License
This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author
- **Your Name**: T.Mahesh
- **Email**: thatimahesh766@gmail.com
- **GitHub**: [GitHub](https://github.com/ThatikondaMahesh/)

---

