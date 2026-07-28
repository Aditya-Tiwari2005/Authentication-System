
# 🔐 Authentication System

A secure Authentication System built using **Node.js**, **Express.js**, and **MongoDB**. It provides user registration, email OTP verification, JWT authentication, refresh token management, and session handling.

---

## 🚀 Features

- ✅ User Registration
- ✅ Email OTP Verification
- ✅ Secure Password Hashing (SHA-256)
- ✅ JWT Access Token Authentication
- ✅ Refresh Token Authentication
- ✅ Session Management
- ✅ Login & Logout
- ✅ Logout from All Devices
- ✅ MongoDB Integration with Mongoose
- ✅ Nodemailer Email Service

---

## 🛠 Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- Nodemailer
- Crypto
- dotenv

---

## 📂 Project Structure

```
Authentication-System
│
├── src
│   ├── config
│   ├── controllers
│   ├── models
│   ├── routes
│   ├── services
│   ├── utils
│   └── app.js
│
├── server.js
├── package.json
└── README.md
```

---

## ⚙️ Installation

Clone the repository

```bash
git clone https://github.com/Aditya-Tiwari2005/Authentication-System.git
```

Go to the project folder

```bash
cd Authentication-System
```

Install dependencies

```bash
npm install
```

Create a `.env` file and add your environment variables.

Run the server

```bash
npm run dev
```

---

## 🔑 Environment Variables

Create a `.env` file in the root directory.

```env
PORT=3000

MONGO_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret

GOOGLE_USER=your_email@gmail.com
GOOGLE_CLIENT_ID=your_client_id
GOOGLE_CLIENT_SECRET=your_client_secret
GOOGLE_REFRESH_TOKEN=your_refresh_token
```

---

## 📌 API Endpoints

### Authentication

| Method | Endpoint | Description |
|---------|----------|-------------|
| POST | `/auth/register` | Register a new user |
| POST | `/auth/verify-email` | Verify email using OTP |
| POST | `/auth/login` | Login user |
| GET | `/auth/me` | Get logged in user |
| POST | `/auth/refresh-token` | Generate new access token |
| POST | `/auth/logout` | Logout current session |
| POST | `/auth/logout-all` | Logout from all devices |

---

## 🔒 Security Features

- Password hashing
- JWT Authentication
- Refresh Tokens
- Email OTP Verification
- HTTP Only Cookies
- Session Management

---

## 👨‍💻 Author

**Aditya Tiwari**

GitHub: https://github.com/Aditya-Tiwari2005