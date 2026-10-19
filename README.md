# 🛒 Ecommerce Website

A full-stack E-commerce web application designed to provide users with a smooth online shopping experience. The project includes a frontend interface and a backend API for managing users, products, and shopping cart operations.

## ✨ Features

- 🛍️ Browse and view products
- 👤 User registration and authentication
- 🛒 Shopping cart management
- 📦 Product and item management
- 🔐 Backend API integration
- 📱 Responsive user interface

## 🧰 Tech Stack

**Frontend**
- React / TypeScript *(verify against your project files)*
- HTML, CSS, JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose

**Tools**
- Visual Studio Code
- Git and GitHub

## 📁 Project Structure

```text
Ecommerce-Site/
├── Backend/
│   ├── controllers/
│   ├── db/
│   ├── middleware/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
├── Frontend/
├── package-lock.json
└── README.md
```

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Tannu-Mahato/Ecommerce-site.git
cd Ecommerce-site
```

### 2. Set up the backend

```bash
cd Backend
npm install
```

Create a `.env` file in the `Backend` folder and configure the MongoDB connection variable required by `db/dbconnect.js`.

### 3. Start the backend

```bash
npm start
```

### 4. Set up the frontend

Open a new terminal:

```bash
cd Frontend
npm install
npm run dev
```

Open the local URL displayed in the terminal.

> Note: The MongoDB connection must be configured before database-dependent features will work. Available scripts and environment variable names may vary according to the project configuration.

## 🔒 Environment Variables

Keep database credentials and API keys in your local `.env` file. Never commit secrets to GitHub.

## 🚀 Future Improvements

- Online payment integration
- Order history and tracking
- Product search and filtering
- Admin dashboard
- Improved security and validation

## 👩‍💻 Author

**Tannu Mahato**

GitHub: [Tannu-Mahato](https://github.com/Tannu-Mahato)

---

If you find this project useful, feel free to explore the repository and share feedback.
