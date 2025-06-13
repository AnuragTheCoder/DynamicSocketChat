# 💬 Chattu - Real-time Chat Application

Chattu is a full-stack real-time chat application built with **MERN Stack**, **Socket.IO**, and **Cloudinary** for media uploads. It features group chat support, friend requests, user roles, and an admin dashboard for managing users and chats.

---
## Live Website Link
-- **https://chatapp-frontend-two-chi.vercel.app**
-- **https://chatapp-frontend-two-chi.vercel.app/admin**

Admin-SecretKey--Hello
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
git clone https://github.com/AnuragTheCoder/DynamicSocketChat.git
cd client
npm i
npm run dev
make a .env in client
VITE_SERVER=""  //your backend erver url
cd ..
cd server
npm i
make e.env
#Add This Environment Variables
PORT=3000
MONGO_URI
CLIENT_URL   Add Your Client URL
JWT_SECRET
NODE_ENV='production'
CLOUDINARY_CLOUD_NAME
CLOUDINARY_API_KEY
CLOUDINARY_API_SECRET
ADMIN_SECRET_KEY=""

