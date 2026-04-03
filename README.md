# 🚀 Code Wave Full Stack

A full-stack web application that allows users to register, log in, and manage posts with a modern and dynamic user interface. The project demonstrates authentication, protected routes, and full CRUD operations using a RESTful API.

---

## 📌 Features

* 🔐 User Authentication (Register & Login)
* 🧑‍💻 Dynamic Navbar (changes based on login status)
* 📝 Create New Post (with title, content, and image)
* 🗂️ Dashboard for managing posts
* ✏️ Full CRUD Operations (Create, Read, Update, Delete)
* 🖼️ Image Upload Support
* 🔒 Protected Routes (only logged-in users can access dashboard)
* 📱 Responsive UI

---

## 🧠 Special Functionality

* Before login → shows **Register | Login**
* After login → shows **Home | Dashboard | Welcome User | Logout**
* Dashboard is only accessible after authentication
* Users can create posts using a form (title, content, image)
* Secure logout removes user session from local storage

---

## 🛠️ Tech Stack

### Frontend

* React.js
* HTML5
* CSS3
* JavaScript (ES6+)

### Backend

* Node.js
* Express.js

### Database

* MongoDB (Mongoose)

### Other Tools

* JWT Authentication
* REST API

---

## 📁 Project Structure

code-wave-full-stack/

├── backend/
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── server.js

├── frontend/
│   ├── src/
│   ├── components/
│   ├── pages/
│   └── package.json

└── README.md

---

## ⚙️ Installation

### 1. Clone the repository

git clone https://github.com/your-username/code-wave-full-stack.git
cd code-wave-full-stack

### 2. Install dependencies

#### Backend

cd backend
npm install

#### Frontend

cd frontend
npm install

---

## ▶️ Run the Application

### Start Backend

cd backend
npm run server

### Start Frontend

cd frontend
npm run dev

---

## 🔑 Environment Variables

Create a `.env` file in the backend folder:

PORT=5000
MONGO_URI=your_mongodb_connection
JWT_SECRET=your_secret_key

---



---

## 🎯 Purpose

This project was built to:

* Practice full-stack web development
* Understand authentication and protected routes
* Implement CRUD operations with a database
* Build a real-world post management system

---


