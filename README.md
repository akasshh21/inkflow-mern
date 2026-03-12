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

```
inkflow-mern
│
├── api/                     # Backend (Node.js + Express)
│   ├── controllers/         # Business logic
│   ├── models/              # MongoDB schemas
│   ├── routes/              # API routes
│   ├── utils/               # Helper utilities
│   └── index.js             # Server entry point
│
├── client/                  # React frontend
│   ├── src/
│   │   ├── components/      # Reusable UI components
│   │   ├── pages/           # Application pages
│   │   ├── redux/           # State management
│   │   ├── firebase.js
│   │   ├── main.jsx         # React entry
│   │   └── index.css
│   │
│   ├── index.html
│   ├── vite.config.js
│   └── tailwind.config.js
│
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```
