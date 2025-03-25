# KFlix - AI-Powered Streaming Platform

![KFlix Banner](homepage2.png)

A full-stack streaming service clone with AI-powered recommendations, featuring real movie streaming, user profiles, and intelligent search powered by Google's Gemini AI.

## 🌟 Live Demo
Experience KFlix live: [https://kflix-mocha.vercel.app/](https://kflix-mocha.vercel.app/)

## 🚀 Features

- 🎥 **Free Movie/TV Streaming** (Powered by third-party services)
- 🤖 **AI-Powered Search** (Gemini 2.0 Flash integration)
- 🔐 **User Authentication**
- 📺 **Watchlist & History**
- 🔍 **Advanced Search** (Movies/TV/People)
- 🎬 **Similar Content Recommendations**
- 📱 **Responsive Design**

## 📸 Screenshots

| Home Screen | AI Chat | Streaming |
|-------------|---------|-----------|
| ![Home Screen](homepage2.png) | ![AI Chat](chatf1.png) | ![Streaming](watchpage2.png) |

## 🛠 Tech Stack

**Frontend**  
![Vite](https://img.shields.io/badge/Vite-B73BFE?style=for-the-badge&logo=vite&logoColor=FFD62E)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Backend**  
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)

**Services**  
![Gemini AI](https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white)
![TMDB API](https://img.shields.io/badge/TMDB_API-01D277?style=for-the-badge&logo=themoviedatabase&logoColor=white)

## 🛠 Installation

### Prerequisites
- Node.js v18+
- MongoDB Atlas account
- TMDB API key
- Google Gemini API key

### Backend Setup
```bash
cd backend
npm install
echo "MONGODB_URI=your_mongodb_uri
TMDB_KEY=your_tmdb_key
GEMINI_KEY=your_gemini_key
JWT_SECRET=your_jwt_secret" > .env
npm start
```

### Frontend Setup
```bash
cd frontend
npm install
# Update Vite config with your IPv4 if needed
npm run dev
```

## 📋 Environment Variables

To run this project, you'll need to configure these environment variables:

### Backend (`.env` file in `/backend`)
```env
# MongoDB Configuration
MONGODB_URI=your_mongodb_atlas_connection_string

# API Keys
TMDB_KEY=your_tmdb_api_v3_key
GEMINI_KEY=your_google_gemini_api_key

# Authentication
JWT_SECRET=your_random_jwt_secret_key
JWT_EXPIRE=24h  # Token expiration time

# Server Configuration
PORT=4000
NODE_ENV=development
```
