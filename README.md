# 📋 TaskFlow – Your Personal Task Manager

Welcome to **TaskFlow**, a clean and simple task management web app built with the **MERN** stack (MongoDB, Express.js, React, Node.js). This project is split into two separate repositories for frontend and backend — but this README gives you the complete picture in one place.

---

## 🚀 Live Demo

* 🔗 Frontend: [todofrontend-9d0i.onrender.com](https://todofrontend-9d0i.onrender.com)
* 🔗 Backend API: [todobackend-kqc1.onrender.com](https://todobackend-kqc1.onrender.com)

---

## ✨ Features

* 🔐 Authentication (Signup/Login with JWT)
* ✅ Add, delete, update tasks
* 🔁 Mark tasks as complete/incomplete
* 🎯 Set task priority: low, medium, high
* 🕓 View creation timestamp for each task
* 📱 Fully responsive modern UI (Tailwind CSS)

---

## 🖥️ Tech Stack

| Layer    | Tech                              |
| -------- | --------------------------------- |
| Frontend | React, Tailwind CSS, React Router |
| Backend  | Node.js, Express.js               |
| Database | MongoDB Atlas                     |
| Auth     | JWT, bcryptjs                     |
| Hosting  | Render (Frontend + Backend)       |

---

## 📁 Repositories

| Part        | Repository Link                                           |
| ----------- | --------------------------------------------------------- |
| 🌐 Frontend | [ToDoFrontend](https://github.com/trevor-09/ToDoFrontend) |
| ⚙️ Backend  | [ToDoBackend](https://github.com/trevor-09/ToDoBackend)   |

---

## 🛠️ How to Run Locally

### 1. Clone Both Repos:

```bash
git clone https://github.com/trevor-09/ToDoFrontend.git
git clone https://github.com/trevor-09/ToDoBackend.git
```

### 2. Run Backend:

```bash
cd ToDoBackend
npm install
node index.js
```

(Optional) Create `.env` with:

```env
MONGOURL=your_mongodb_url
JWT_SECRET=your_jwt_secret
```

### 3. Run Frontend:

```bash
cd ../ToDoFrontend
npm install
npm start
```

Frontend will run at `http://localhost:3000`
Backend will run at `http://localhost:8080`

---

## 📷 Screenshots

### 🔐 Signup Page
![Signup Page](https://github.com/trevor-09/TaskFlow/blob/main/screenshots/Screenshot%202025-07-03%20221245.png?raw=true)

---

### 🔑 Login Page
![Login Page](https://github.com/trevor-09/TaskFlow/blob/main/screenshots/Screenshot%202025-07-03%20221235.png?raw=true)

---

### 🗂️ Task Dashboard
![Dashboard](https://github.com/trevor-09/TaskFlow/blob/main/screenshots/Screenshot%202025-07-03%20221951.png?raw=true)



---

## 💡 Inspiration

Built as part of a full-stack bootcamp project, the goal of TaskFlow is to demonstrate how a simple idea can be brought to life with clean UI and proper backend design.

---

## 🪄 License

This project is open-source and available for educational and personal portfolio use.

---

> Made by Abhay Raj
