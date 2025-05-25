# 💬 Chattu - Real-time Chat Application

Chattu is a full-stack real-time chat application built with **MERN Stack**, **Socket.IO**, and **Cloudinary** for media uploads. It features group chat support, friend requests, user roles, and an admin dashboard for managing users and chats.

---

## 🚀 Features

### 👥 User Features
- **Authentication** (Signup/Login with secure JWT cookies)
- **Profile Update** (name, avatar, and email)
- **Friend Request System**
  - Send, accept, and reject friend requests
  - See all friends
- **Real-time Chat**
  - 1-on-1 chat
  - Group chat
  - Message seen status
  - Typing indicators
- **Media Upload**
  - Send images or files in chat via Cloudinary

### 👨‍💼 Admin Features
- Admin Dashboard with:
  - Total Users
  - Total Chats
  - List of all users with roles
  - Delete user/chat
  - Promote user to admin

---

## 📸 Screenshots

| Chat Interface | Friend Requests | Group Chat |
|----------------|-----------------|-------------|
| ![](./Screenshot%202025-05-25%20133646.png) | ![](./Screenshot%202025-05-25%20133647.png) | ![](./Screenshot%202025-05-25%20134054.png) |

| Chat with Media | Admin Dashboard | Create Group |
|-----------------|------------------|--------------|
| ![](./Screenshot%202025-05-25%20144114.png) | ![](./Screenshot%202025-05-25%20144144.png) | ![](./Screenshot%202025-05-25%20144155.png) |

| User List | Chat Window | Add Users to Group |
|-----------|--------------|---------------------|
| ![](./Screenshot%202025-05-25%20144221.png) | ![](./Screenshot%202025-05-25%20144257.png) | ![](./Screenshot%202025-05-25%20144323.png) |

| Group Settings | Admin User Table | Message Info |
|----------------|-------------------|---------------|
| ![](./Screenshot%202025-05-25%20144335.png) | ![](./Screenshot%202025-05-25%20144348.png) | ![](./Screenshot%202025-05-25%20144409.png) |

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS, Axios
- **Backend**: Node.js, Express.js, Socket.IO
- **Database**: MongoDB
- **File Storage**: Cloudinary
- **Authentication**: JWT + HttpOnly cookies
- **Hosting**: Render (Backend), Vercel/Netlify (Frontend)

---

## 🧪 How to Run Locally

### 1. Clone Repositories
```bash
git clone https://github.com/AnuragTheCoder/chatapp-server.git
git clone https://github.com/AnuragTheCoder/chatapp-frontend.git
