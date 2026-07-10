# 🚀 ORVICO

ORVICO is a full-stack freelance platform designed to connect customers with skilled craftsmen and service providers. The platform enables users to browse available services, request jobs, communicate with professionals, and manage their accounts through a modern web interface.

The project follows a multi-repository architecture consisting of three independent applications:

* 🌐 **Frontend** – Customer-facing web application built with React.
* ⚙️ **Backend** – RESTful API built with Node.js, Express, and MongoDB.
* 📊 **Dashboard** – Admin panel for managing users, services, and platform data.

---

# 📦 Project Architecture

```text
                    ORVICO Platform

                    ┌──────────────┐
                    │   Frontend   │
                    │    React     │
                    └──────┬───────┘
                           │
                      REST API
                           │
                    ┌──────▼───────┐
                    │   Backend    │
                    │ Node + Express│
                    └──────┬───────┘
                           │
                      MongoDB
                           │
                    ┌──────▼───────┐
                    │   Database   │
                    └──────────────┘

              ┌──────────────────────┐
              │   Admin Dashboard    │
              │       React          │
              └──────────────────────┘
```

---

# ✨ Main Features

* 👤 User Registration & Login
* 🔐 JWT Authentication
* 👨‍🔧 Service Provider Profiles
* 📋 Browse Available Services
* 🔍 Search Services
* 📂 Category-based Services
* 📨 Contact & Communication
* 📤 Image Upload
* 📧 Email Notifications
* 🛡️ Protected Routes
* 📊 Admin Dashboard
* 📱 Responsive Design
* 🌐 RESTful API
* 📄 Swagger API Documentation

---

# 🛠️ Technology Stack

## Frontend

* React
* Vite
* JavaScript (ES6+)
* Bootstrap
* React Bootstrap
* Axios
* React Router DOM
* Formik
* Yup
* JWT Decode
* React Icons
* Font Awesome

---

## Backend

* Node.js
* Express.js
* MongoDB
* Mongoose
* JWT
* Bcrypt
* Nodemailer
* Multer
* Formidable
* Swagger
* UUID
* Dotenv
* CORS

---

## Admin Dashboard

* React
* Vite
* Axios
* Bootstrap
* React Bootstrap
* React Router DOM

---

# 📁 Repositories

| Repository       | Description      |
| ---------------- | ---------------- |
| ORVICO           | Main Project     |
| ORVICO-FRONT-END | Customer Website |
| ORVICO-BACK-END  | REST API         |
| DASHBOARD        | Admin Dashboard  |

---

# 🔐 Authentication

The platform uses **JWT (JSON Web Tokens)** for authentication.

Features include:

* User Login
* User Registration
* Protected API Routes
* Token Validation
* Password Hashing using Bcrypt

---

# 📂 Backend Features

* RESTful API
* MongoDB Database
* Authentication
* File Upload
* Email Sending
* API Documentation with Swagger
* Environment Variables
* Error Handling

---

# 💻 Frontend Features

* Modern React Architecture
* Dynamic Routing
* API Integration
* Form Validation
* Authentication Flow
* Responsive UI
* Protected Pages

---

# 📊 Dashboard Features

The admin dashboard allows administrators to:

* Manage Users
* Manage Service Providers
* Manage Services
* Monitor Platform Data
* Control System Content

---

# 🚀 Getting Started

Clone each repository separately:

```bash
git clone https://github.com/AhmedFathy114/ORVICO-FRONT-END

git clone https://github.com/AhmedFathy114/ORVICO-BACK-END

git clone https://github.com/AhmedFathy114/DASHBOARD
```

Install dependencies:

```bash
npm install
```

Run each project:

Frontend

```bash
npm run dev
```

Backend

```bash
npm start
```

Dashboard

```bash
npm run dev
```

---

# 🔮 Future Improvements

* Online Payments
* Live Chat
* Ratings & Reviews
* Push Notifications
* Real-time Messaging
* Service Booking Calendar
* Mobile Application
* Multi-language Support

---
