# Forever E-Commerce Platform

A full-stack e-commerce web application built using the MERN stack, featuring a customer storefront, secure authentication, online payments, order management, and a separate admin dashboard for managing products and orders.

## 🚀 Live Demo

- **Frontend:** [Live Website](https://forever-frontend-nu-ebon.vercel.app/)
- **Admin Dashboard:** [Admin Panel](https://forever-admin-pi.vercel.app/add)

## 📌 Features

### Customer
- User registration and login
- JWT-based authentication
- Browse products
- Product search and filtering
- Product details and multiple product images
- Add/remove products from cart
- Update cart quantities
- Place orders
- Stripe Checkout payment
- Cash on Delivery (COD)
- Order tracking and order status updates

### Admin
- Secure admin authentication
- Add, update, and remove products
- Upload product images using Cloudinary
- Manage product inventory
- View and manage customer orders
- Update order status
- Separate admin dashboard

## 🛠️ Tech Stack

### Frontend
- React.js
- JavaScript
- React Router
- Context API
- Axios
- Tailwind CSS
- Vite

### Backend
- Node.js
- Express.js
- REST APIs
- JWT Authentication
- Bcrypt

### Database
- MongoDB
- Mongoose

### Services
- Stripe
- Cloudinary

## 🏗️ Project Structure

```text
Forever-ecommerce/
│
├── frontend/        # Customer-facing React application
│
├── admin/           # Admin dashboard
│
├── backend/         # Node.js + Express backend
│
├── .gitignore
└── README.md
