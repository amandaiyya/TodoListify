# TodoListify 📝

**TodoListify** is a full-stack production-ready Todo application designed for personal productivity. It offers a secure, minimalist, and responsive interface for users to manage their tasks. The application is built with a **Node.js + Express** backend and a **Vanilla JavaScript (Vite)** frontend.

🌐 Live App: [https://todolistify.onrender.com](https://todolistify.onrender.com)

## 🧪 Test Credentials

You can use the following credentials to explore the app without creating a new account:

```
📧 Email:    newTest@test.com  
🔑 Password: newtest1234
```

> ⚠️ These credentials are for demo purposes only. Please do not modify or delete test data for other users.

---

## 🌟 Features

### 🔐 Authentication & Authorization
- Secure JWT-based authentication system
- Access tokens and refresh tokens stored in HTTP-only cookies
- Login, Register, Logout, and Token Refresh endpoints
- Bcrypt password hashing and verification via model hooks

### 👤 User Management
- Register new users
- Login and logout
- Update username, email, and password
- All changes are validated and securely processed

### ✅ Todo Functionality
- Full CRUD operations on todos
- Each user has their own list of todos
- Pagination for better task management
- Minimalist UI for quick task input and editing

### ⚙️ Tech Stack
#### Backend
- Node.js + Express
- MongoDB with Mongoose
- JWT (Access + Refresh tokens)
- bcrypt for password hashing
- cookie-parser
- Modular code using:
  - Routes
  - Controllers
  - Middleware
  - Database Models
  - Pagination logic

#### Frontend
- Vanilla JavaScript
- HTML5 & CSS3 (Responsive and Minimal UI)
- Built and served using **Vite**
- Handles:
  - Auth flows (register, login, logout)
  - Token refresh logic
  - Todo CRUD operations
  - Pagination UI & interactions
  - User profile update (username, email, password)

---

## 🛡️ Security Features
- HTTP-only cookies for refresh tokens
- Passwords hashed with bcrypt
- Middleware to verify tokens and protect routes
- Token expiration and rotation handling

---

## 🎨 UI/UX
- Built with responsive and minimalist design principles
- Smooth client-side interactions using Vanilla JS
- Intuitive task and user profile management

---

## 📦 Deployment
This application is deployed and live at:  
🔗 [https://todolistify.onrender.com](https://todolistify.onrender.com)

> ⚠️ **Note:** The backend is deployed on **Render’s free tier**, which means it may take **20–30 seconds to wake up** after being idle. If you get no response initially, please wait or **refresh the page 1–2 times**.

---

## 🙌 Contribution
This project is currently designed for personal use and learning purposes, but contributions, issues, and suggestions are always welcome.
