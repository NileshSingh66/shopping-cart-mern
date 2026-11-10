# 🛒 Shopping Cart – MERN Stack E-Commerce Application

A full-stack e-commerce application built using the MERN stack, featuring user authentication, product browsing, shopping cart management, and online payment integration.

## 🚀 Features

- **User Authentication:** User registration and login functionality.
- **Product Browsing:** Browse and view available products.
- **Shopping Cart:** Add products to the cart and manage cart items.
- **Cart Management:** Update and remove products from the shopping cart.
- **State Management:** Manage authentication and cart state using Redux Toolkit.
- **Payment Integration:** Stripe integration for online payment processing.
- **Responsive UI:** User-friendly interface built with React and Tailwind CSS.
- **REST API:** Backend API endpoints built using Node.js and Express.js.
- **Database Integration:** MongoDB with Mongoose for data management.

## 🛠️ Tech Stack

**Frontend**
- React.js
- Vite
- Redux Toolkit
- React Router
- Tailwind CSS
- JavaScript

**Backend**
- Node.js
- Express.js
- MongoDB
- Mongoose
- JSON Web Token (JWT)

**Payment Integration**
- Stripe

**Development Tools**
- Git & GitHub
- VS Code
- npm

## 📂 Project Structure

```text
shopping-cart-mern/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── app/
│   │   │   ├── slices/
│   │   │   └── store.js
│   │   ├── components/
│   │   ├── helpers/
│   │   ├── pages/
│   │   ├── App.jsx
│   │   └── main.jsx
│   └── package.json
│
├── server/
│   ├── config/
│   ├── controllers/
│   ├── middlewares/
│   ├── models/
│   ├── routes/
│   ├── index.js
│   └── package.json
│
└── README.md
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/NileshSingh66/shopping-cart-mern.git
```

### 2. Navigate to the Project

```bash
cd shopping-cart-mern
```

### 3. Install Backend Dependencies

```bash
cd server
npm install
```

### 4. Configure Environment Variables

Create a `.env` file inside the `server` directory and configure the required MongoDB connection string, JWT secret, Stripe secret key, and other variables referenced in the source code.

### 5. Start the Backend Server

```bash
npm run dev
```

### 6. Install Frontend Dependencies

Open another terminal:

```bash
cd client
npm install
```

### 7. Start the Frontend

```bash
npm run dev
```

Open the local URL displayed in your terminal (typically `http://localhost:5173`).

## 🔐 Environment Configuration

The application requires configuration for:

- MongoDB database connection
- JWT authentication
- Stripe payment integration
- Backend/frontend API communication

**Note:** Never upload `.env` files, passwords, or private API keys to GitHub.

## 💳 Payment Integration

The application uses Stripe for payment processing and online transaction handling.

Configure your Stripe credentials before testing payment functionality.

## 📌 Future Enhancements

- Product search and filtering
- Product categories
- Order history and tracking
- User profile management
- Admin dashboard
- Improved checkout experience

