# 💬 Full Stack Chat App

A real-time chat application built with **Node.js**, **Express**, **MongoDB**, **React**, and **Socket.io**.

---

## 🚀 Features
- 🔑 User authentication (JWT + cookies)
- 💬 Real-time messaging with Socket.io
- 📂 MongoDB database with Mongoose
- 🌐 Full-stack setup with React frontend & Node backend

---

## 📦 Installation

### 1️⃣ Clone the repository
```bash
git clone https://github.com/yourusername/chat-app.git
cd chat-app

cd backend
npm install

cd frontend
npm install

###Create .ENV file and add following
 
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

NODE_ENV=development

npm run build

npm run dev

npm start

