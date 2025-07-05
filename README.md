# 💬 ChatApp - MERN Stack Real-Time Chat Application

ChatApp is a full-stack real-time chat application built using the **MERN Stack (MongoDB, Express, React, Node.js)**. It allows users to securely register, authenticate, upload profile pictures via Cloudinary, and chat in real-time through private and group conversations.

---

## 🚀 Features

### 🔐 Authentication & Security
- JWT-based login and registration
- Secure password hashing using `bcrypt`
- Protected routes with middleware

### 👤 User Features
- Upload and update profile picture (Cloudinary)
- Search registered users by name or email
- View all active conversations

### 💬 Messaging
- Real-time one-on-one and group messaging using Socket.IO
- Typing indicators and auto-scroll
- Send text messages to registered users

### 👥 Group Chat Management
- Create and rename group chats
- Add or remove users from a group
- Delete group chats (admin only)

---

## 🛠️ Tech Stack

### Frontend
- React.js
- Material-UI (MUI)
- Axios
- Socket.IO Client

### Backend
- Node.js + Express.js
- MongoDB + Mongoose
- JSON Web Token (JWT)
- bcrypt for password hashing
- Cloudinary for image uploads
- Socket.IO for real-time communication

---

## 📦 Installation

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/chatapp.git
cd chatapp
