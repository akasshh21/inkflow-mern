# InkFlow – MERN Blog Platform

A full-stack blogging platform built using the **MERN stack (MongoDB, Express.js, React, Node.js)**.  
The application allows users to create, edit, search, and manage blog posts with secure authentication and an admin dashboard.


---

## Features

• User authentication with email/password and Google OAuth  
• Create, edit, update, and delete blog posts  
• Admin dashboard for managing users, posts, and comments  
• Search and filter functionality for blog posts  
• Responsive UI built with React and Tailwind CSS  
• Secure backend APIs using JWT authentication  

---

## Tech Stack

**Frontend**
- React
- Redux Toolkit
- Tailwind CSS
- React Router

**Backend**
- Node.js
- Express.js

**Database**
- MongoDB
- Mongoose

**Authentication**
- JWT
- Google OAuth

---

## Project Structure

inkflow-mern/
│
├── api/ # Backend (Node.js + Express)
│ ├── controllers/ # Business logic for routes
│ ├── models/ # MongoDB schemas using Mongoose
│ ├── routes/ # API route definitions
│ ├── utils/ # Helper functions and middleware
│ └── index.js # Server entry point
│
├── client/ # Frontend (React application)
│ ├── src/
│ │ ├── components/ # Reusable UI components
│ │ ├── pages/ # Application pages
│ │ ├── redux/ # Redux state management
│ │ ├── firebase.js # Firebase configuration
│ │ ├── main.jsx # React entry point
│ │ └── index.css
│ │
│ ├── index.html
│ ├── vite.config.js
│ └── tailwind.config.js
│
├── package.json # Project dependencies
├── package-lock.json
├── .gitignore
└── README.md
