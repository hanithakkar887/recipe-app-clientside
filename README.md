# 🍲 Recipe App (Full-Stack)

A **full-stack Recipe App** built with **React, Node.js, Express, and MongoDB**.  
The app allows users to **register, login, manage recipes**, and explore a rich recipe collection with a **responsive, interactive UI** enhanced by **Lucide icons**.

## 🚀 Features

### Frontend (React)
- Built with **React** and **Tailwind CSS** for a modern, responsive UI.
- **Lucide icons** used for intuitive and visually appealing UI components.
- Features include **search, recipe browsing, wishlist, and interactive recipe cards**.
- Fully responsive design for **mobile, tablet, and desktop**.

### Backend (Node.js + Express + MongoDB)
- **User authentication** with JWT (registration & login).
- **Protected routes** for secure recipe management.
- **MongoDB** database integration to store user accounts and recipes.
- RESTful API endpoints for **CRUD operations on recipes**.

### General
- Clean, maintainable code with modular structure.
- Optimized performance and smooth user experience.
- Easily deployable: **Netlify for frontend**, **Render for backend**.

## 🌐 Live Demo
[Recipe App Live](https://recipe-app-fullstack.netlify.app/)

## 💻 GitHub Repositories
[Frontend (React)](https://github.com/hanithakkar887/recipe-app-frontend/tree/main/client_Side)  
[Backend (Node.js + Express)](https://github.com/hanithakkar887/recipe-app-backend)

## 🛠 Tech Stack
- **Frontend:** React, Tailwind CSS, Lucide Icons, JavaScript, HTML5, CSS3  
- **Backend:** Node.js, Express.js, MongoDB, JWT, bcrypt  
- **Deployment:** Netlify (Frontend), Render (Backend)

## 📌 How to Run Locally

### Frontend
```bash
cd recipe-app-clientside
npm install
npm run dev

```bash
# 2️⃣ Backend Setup
# Clone the backend repository
git clone https://github.com/hanithakkar887/recipe-app-backend.git
# Navigate to the backend folder
cd recipe-app-backend
# Install dependencies
npm install
# Create a .env file and add your environment variables (MONGO_URI, JWT_SECRET, PORT)
# Example:
# MONGO_URI=your_mongodb_connection_string
# JWT_SECRET=your_jwt_secret
# PORT=5000
# Start the backend server
node server.js
