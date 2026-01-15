# 🌍 Streamify - Language Exchange & Real-Time Communication Platform
Experience seamless communication on a powerful **language exchange platform** designed for global interaction and real-time collaboration. This feature-rich application connects language learners worldwide through chat and video, making learning interactive, social, and engaging.

DEMO VIDEO : https://drive.google.com/file/d/1k68PuPulRIHPlDPXwh0BdGiGoISIurX2/view?usp=sharing

RENDER DEPLOYMENT :  https://streamify-final.onrender.com

---

## 🚀 Project Highlights (Hackathon Build)

* 💬 **Real-time messaging** with live typing indicators and message reactions
* 📹 **One-on-one & group video calls** with screen sharing and recording support
* 🔐 **Secure JWT authentication** with protected routes
* 🎨 **32 unique UI themes** for a fully personalized user experience
* ⚡ **Scalable real-time features** powered by Stream
* 🌐 **Global language learning focus**, enabling users to connect and practice languages with people across the world

---

## 🛠️ Tech Stack

* **Frontend:** React, TailwindCSS, TanStack Query
* **Backend:** Node.js, Express.js
* **Database:** MongoDB
* **State Management:** Zustand
* **Real-time Communication:** Stream

---

## 🌱 Use Case

This chat application is **personalized for language learners** who want to practice and learn new languages by connecting with native speakers or fellow learners through **text chat and video calls**, anytime and anywhere.

---

## 🔑 Environment Setup

### Backend (`/backend/.env`)

```env
PORT=5001
MONGO_URI=your_mongo_uri
STEAM_API_KEY=your_steam_api_key
STEAM_API_SECRET=your_steam_api_secret
JWT_SECRET_KEY=your_jwt_secret
NODE_ENV=development
```

---

### Frontend (`/frontend/.env`)

```env
VITE_STREAM_API_KEY=your_stream_api_key
```

---

## ▶️ Running the Application

### Start the Backend

```bash
cd backend
npm install
npm run dev
```

---

### Start the Frontend

```bash
cd frontend
npm install
npm run dev
```

---
