# 🚀 Backend YouTube System

A scalable backend system for a YouTube-like video sharing platform built with Node.js, Express.js, and MongoDB. It provides APIs for user authentication, video management, comments, likes, and subscriptions.

---

## 📌 Features

- 🔐 JWT Authentication (Login / Register)
- 📹 Video Upload & Management
- 👍 Like / Dislike Functionality
- 💬 Comment System
- 🔔 Subscribe / Unsubscribe Channels
- ☁️ Cloudinary Media Storage
- 📡 RESTful APIs

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- MongoDB
- Mongoose
- JWT (JSON Web Token)
- Multer
- Cloudinary

---

## 📁 Project Structure

```
Backend-YouTube-System/
│
├── src/
│   ├── controllers/
|   ├── db/
│   ├── models/
│   ├── routes/
│   ├── middlewares/
│   ├── utils/
|   ├── app.js
|   ├── constants.js
│   └── index.js
│
├── public/
├── .env
└── package.json
```

---

## ⚙️ Installation

1. Clone the repository

```bash
git clone https://github.com/MontuSherasiya/Backend-YouTube-System.git
```

2. Navigate to project

```bash
cd Backend-YouTube-System
```

3. Install dependencies

```bash
npm install
```

4. Create `.env` file

```
PORT=5000
MONGODB_URI=your_mongodb_url
JWT_SECRET=your_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

5. Run server

```bash
npm run dev
```

---

## 📡 API Endpoints

### 🔐 Auth
- POST /api/v1/users/register
- POST /api/v1/users/login
- GET /api/v1/users/profile

### 📹 Videos
- POST /api/v1/videos/upload
- GET /api/v1/videos
- GET /api/v1/videos/:id
- DELETE /api/v1/videos/:id

### 💬 Comments
- POST /api/v1/comments
- GET /api/v1/comments/:videoId

### 👍 Likes & Subscriptions
- POST /api/v1/like/:videoId
- POST /api/v1/subscribe/:channelId

---

## 🔐 Environment Variables

| Variable | Description |
|----------|------------|
| PORT | Server Port |
| MONGODB_URI | MongoDB Connection URL |
| JWT_SECRET | Secret Key |
| CLOUDINARY_CLOUD_NAME | Cloudinary Name |
| CLOUDINARY_API_KEY | Cloudinary Key |
| CLOUDINARY_API_SECRET | Cloudinary Secret |

---

## 🚀 Future Improvements

- Video search functionality
- Recommendation system
- Analytics dashboard
- Video streaming optimization

---

## 👨‍💻 Author

Montu Sherasiya  
GitHub: https://github.com/MontuSherasiya

---