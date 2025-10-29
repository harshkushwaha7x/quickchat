<div align="center">

# QUICKCHAT 💬

**QuickChat** is a full-stack real-time messaging platform built with modern web technologies. It enables **instant communication**, **secure authentication**, and **seamless chatting** — designed for individuals and teams who value fast and reliable conversations.

[Live Demo](https://quick-chat-nine-beta.vercel.app) • [Portfolio](https://harshkushwaha7x.github.io/Portflio.2/) • [GitHub](https://github.com/harshkushwaha7x/QuickChat)

</div>

---

<p align="center">
  <a href="https://github.com/harshkushwaha7x/QuickChat"><img src="https://img.shields.io/github/last-commit/harshkushwaha7x/QuickChat?style=flat-square" alt="last commit"></a>
  <a href="https://github.com/harshkushwaha7x/QuickChat"><img src="https://img.shields.io/github/languages/top/harshkushwaha7x/QuickChat?style=flat-square" alt="languages"></a>
  <a href="https://github.com/harshkushwaha7x/QuickChat/blob/main/LICENSE"><img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="license" /></a>
  <img src="https://img.shields.io/badge/version-1.0.0-success?style=flat-square" alt="version" />
</p>

</div>

---

## 💬 Overview

**QuickChat** is a full-stack real-time chat application enabling users to communicate instantly with live message updates, authentication, and profile management.
Built using **Socket.io**, **MERN Stack**, and **Cloudinary**, it delivers a fast, responsive, and scalable messaging experience.

Core highlights:

* ⚡ **Real-Time Messaging**: Instant delivery powered by Socket.io
* 🔐 **Secure Authentication**: JWT-based login system
* 👥 **User Profiles**: Status, avatars, and personalization
* 📱 **Responsive UI**: Optimized for all devices
* 🔊 **Smart Notifications**: Message and activity alerts

---

## 🚀 Key Features

### ⚡ Real-Time Communication

* Instant message delivery using Socket.io
* Typing indicators and online/offline status
* Read receipts and message history
* Notifications for new messages

### 👤 User Management

* JWT authentication for secure login
* Encrypted password storage with bcrypt
* Profile updates with avatar uploads
* Session persistence and token validation

### 🧠 Enhanced Experience

* Clean, modern interface with TailwindCSS
* Dark and light mode support
* Emoji and media sharing (Cloudinary)
* Search messages and users

---

## ⚙️ Tech Stack

### Frontend

* React 19.1.1 + Vite
* Tailwind CSS
* Socket.io Client
* Axios & React Router DOM
* React Context API
* React Icons

### Backend

* Node.js + Express
* MongoDB & Mongoose
* Socket.io
* JWT Authentication
* bcryptjs
* Cloudinary for file storage

### DevOps / Cloud

* Vercel (Frontend)
* Render / Railway (Backend)
* MongoDB Atlas (Database)
* GitHub Actions for CI/CD

---

## 🧩 Architecture

```text
QuickChat/
├── client/                  # React Frontend (Vite + Tailwind)
│   ├── src/
│   │   ├── components/     # ChatContainer, Sidebar, etc.
│   │   ├── context/        # AuthContext, ChatContext
│   │   ├── pages/          # Login, Chat, Profile
│   │   ├── assets/         # Images, icons, CSS
│   │   └── main.jsx        # Entry point
│   ├── package.json
│   └── vite.config.js
│
├── server/                 # Express Backend + Socket.io
│   ├── controllers/        # User & Message logic
│   ├── models/             # User & Message schemas
│   ├── routes/             # API route definitions
│   ├── middleware/         # Auth middleware
│   ├── config/             # DB & Cloudinary setup
│   └── server.js           # Express + Socket.io server
│
├── .gitignore
├── LICENSE
└── README.md
```

---

## 🧰 Getting Started

### Prerequisites

* Node.js v18+
* MongoDB Atlas account
* Cloudinary account (for image uploads)

### Installation

```bash
git clone https://github.com/harshkushwaha7x/QuickChat.git
cd QuickChat
```

#### Install Dependencies

```bash
cd client && npm install
cd server && npm install
```

#### Environment Variables

**Client (.env):**

```env
VITE_BACKEND_URL=http://localhost:5000
```

**Server (.env):**

```env
MONGODB_URI=your-mongodb-uri
JWT_SECRET=your-jwt-secret
CLOUDINARY_CLOUD_NAME=your-cloudinary-name
CLOUDINARY_API_KEY=your-api-key
CLOUDINARY_API_SECRET=your-api-secret
PORT=5000
```

#### Run Project

```bash
# Terminal 1 - Start Backend (Port 5000)
cd server && npm run server

# Terminal 2 - Start Frontend (Port 5173)
cd client && npm run dev
```

---

## 💡 Real-Time Events

* `new-user` — When a user connects
* `send-message` — Emit message to recipient
* `receive-message` — Receive live messages
* `typing` / `stop-typing` — Show typing indicators

---

## 🔌 API Endpoints

### Authentication

* `POST /api/auth/register` — Register new user
* `POST /api/auth/login` — User login
* `GET /api/auth/me` — Get current user

### Users

* `GET /api/users` — Get all users
* `GET /api/users/:id` — Get specific user
* `PUT /api/users/:id` — Update profile

### Messages

* `GET /api/messages/:chatId` — Fetch messages
* `POST /api/messages` — Send message

---

## ☁️ Deployment

* Frontend → Vercel
* Backend → Render / Railway
* Database → MongoDB Atlas

---

## ⚡ Performance

* Optimized Vite builds
* WebSocket-based real-time messaging
* Scalable architecture
* Secure JWT authentication

---

## 🤝 Contributing

1. Fork this repository
2. Create a feature branch (`git checkout -b feature-name`)
3. Commit your changes (`git commit -m "Add new feature"`)
4. Push & open a Pull Request

---

## 🪪 License

This project is licensed under the **MIT License** — see [LICENSE](https://github.com/harshkushwaha7x/QuickChat/blob/main/LICENSE).

---

## 📬 Contact

**Harsh Kushwaha** — Developer & Maintainer

* Portfolio: [https://harshkushwaha7x.github.io/Portfolio](https://harshkushwaha7x.github.io/Portfolio)
* GitHub: [https://github.com/harshkushwaha7x](https://github.com/harshkushwaha7x)
* LinkedIn: [https://www.linkedin.com/in/harshkushwaha7x/](https://www.linkedin.com/in/harshkushwaha7x/)
* Email: [harshkushwaha4151@gmail.com](mailto:harshkushwaha4151@gmail.com)

---

<div align="center">

**QUICKCHAT** – Connect Instantly. Chat Seamlessly. ⚡
Built by <b>Harsh Kushwaha</b>

</div>

---
