# 💬 Talkie

![MERN Stack](https://img.shields.io/badge/Stack-MERN-blueviolet)
![Socket.IO](https://img.shields.io/badge/Real--Time-Socket.IO-green)
![Tailwind CSS](https://img.shields.io/badge/Styled%20With-TailwindCSS-38B2AC)
![DaisyUI](https://img.shields.io/badge/UI-DaisyUI-ff69b4)
![Zustand](https://img.shields.io/badge/State-Zustand-yellowgreen)
![MongoDB Atlas](https://img.shields.io/badge/Database-MongoDB%20Atlas-47A248)
![Cloudinary](https://img.shields.io/badge/Image%20Upload-Cloudinary-blue)
![JWT](https://img.shields.io/badge/Auth-JWT-orange)

---

## 🔗 Live Demo

🚀 **[View BlahBlah on Render](https://blahblah-6gob.onrender.com)**

---

## 🧾 Overview

**BlahBlah** is a real-time chat web app built with the **MERN stack**. It supports secure, real-time messaging with image sharing, profile customization, and theme switching. Built with a sleek UI powered by **Tailwind CSS** and **DaisyUI**, and real-time communication handled via **Socket.IO**, the app uses **MongoDB Atlas** for scalable cloud-based data storage.

---

## 🧑‍💻 Tech Stack

### 🖥️ Frontend

- React.js  
- Tailwind CSS + DaisyUI  
- Zustand (State Management)  
- Axios  
- Lucide React (Icons)  
- React Router DOM  

### 🛠️ Backend

- Node.js + Express.js  
- MongoDB Atlas + Mongoose  
- Socket.IO  
- JSON Web Token (JWT)  
- bcryptjs  
- Cloudinary (Image Uploads)
- Cors
- Cookie-parser   

---

## ✨ Features

- 🔐 JWT-based authentication (login/signup)  
- 💬 Real-time one-on-one chat using Socket.IO  
- 🖼️ Send and receive images in chat  
- 🧑 Upload and update user profile pictures via Cloudinary  
- 🟢 Real-time user presence (online/offline)  
- 🎨 Theme switcher with multiple DaisyUI themes  
- 🌐 MongoDB Atlas for cloud-hosted database  
- 🗂️ Chat history persistence  

---

## 📁 Project Structure

```
BlahBlah/
├── backend/
│   └── src/
│       ├── controllers/              # Route handler logic
│       ├── lib/                      # DB connection, Cloudinary config, etc.
│       ├── middleware/               # JWT auth, Multer, error handling
│       ├── models/                   # Mongoose schemas
│       ├── routes/                   # Express routers
│       └── index.js                  # Server entry point
│
├── frontend/
|   ├── public/
│   ├── src/
│   │   ├── components/               # Reusable UI components
│   │   ├── constants/                # App-wide constants
│   │   ├── lib/                      # Axios instance, utility functions
│   │   ├── pages/                    # Page-level views
│   │   ├── store/                    # Zustand store
│   │   ├── App.jsx                   # Root app component
│   │   ├── main.jsx                  # ReactDOM entry point
│   │   ├── index.css                 # Global styles
│   │   └── index.html                # HTML entry point
│   ├── tailwind.config.js
│   ├── postcss.config.js
│   └── package.json
```
---

## 🖼️ Screenshots

### 🔐 Login Page
<img width="1882" height="865" alt="Screenshot 2025-07-31 011401" src="https://github.com/user-attachments/assets/63b28da9-799b-4c08-b5b2-3be5db01817b" />

### 💬 Chat Interface with Image Sharing
<img width="1889" height="864" alt="Screenshot 2025-07-30 181744" src="https://github.com/user-attachments/assets/8fc196cf-a92a-4d87-9df7-52ebcf71ba7f" />

### 🎨 Theme Switcher in Settings
<img width="1884" height="710" alt="Screenshot 2025-07-30 181215" src="https://github.com/user-attachments/assets/431492d8-2fee-4483-928c-abef6e455354" />

---

## 🚀 Future Enhancements

- ✏️ Typing indicators  
- 🔔 Message notifications  
- 🧑‍🤝‍🧑 Group chat functionality  
- 📎 File/document sharing    
- 🕵️‍♂️ Message read receipts  

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).
