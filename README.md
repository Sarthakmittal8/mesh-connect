# 🧠 Mesh Connect

> An Intelligent Emotion-Aware Messaging Network

Mesh Connect is a real-time communication platform engineered to make digital conversations emotionally responsive. Instead of static interfaces, the system dynamically adapts its visual experience based on detected sentiment, creating a context-aware messaging environment.

Designed with scalability, modularity, and performance in mind, Mesh Connect blends affective computing with modern full-stack architecture to deliver adaptive, secure, and real-time communication.

---

## 🔎 What Makes It Different?

Unlike traditional chat applications, Mesh Connect analyzes conversational tone and instantly modifies the user interface to reflect emotional context. This creates a responsive communication loop between content and presentation.

The platform supports over 30 emotional states, each mapped to a dynamic theme transformation.

---

## 🧩 Core Capabilities

- Emotion-aware UI transformation across 30+ sentiment states  
- Real-time bidirectional messaging powered by Socket.io  
- Secure JWT authentication using HTTP-only cookies  
- CSRF protection and secure API handling  
- Cloudinary-based media storage and optimization  
- Zustand-powered lightweight global state management  
- Fully responsive interface built with TailwindCSS and DaisyUI  

---

## 🏗️ Architecture Overview

Mesh Connect follows a modular client-server model with clear separation of responsibilities.

### 🖥 Frontend Layer

- React 18 with Vite for fast builds and optimized bundling  
- TailwindCSS + DaisyUI for theme-driven design system  
- Zustand for predictable state management  
- Socket.io client for instant event-driven communication  
- Axios with interceptors for centralized API handling  
- React Router v6 with protected route implementation  

---

### ⚙️ Backend Layer

- Express.js structured using MVC architecture  
- MongoDB with Mongoose ODM for schema modeling  
- JWT authentication using secure HTTP-only cookies  
- Socket.io server with user session tracking  
- Cloudinary for cloud-based image storage  
- Robust CORS configuration, validation, and error handling  

---

## 🧪 Supported Emotional States

Mesh Connect recognizes and adapts to emotional tones such as:

- Positive: Happy, Grateful, Supportive  
- Negative: Sad, Angry, Anxious  
- Professional: Formal, Informative, Urgent  
- Casual: Humorous, Relaxed  
- Contextual: Apologetic, Romantic, Surprised  
- Neutral and conversational tones  

Each detected emotion triggers a unique visual theme adjustment, enhancing contextual awareness during interaction.

---

## 🔁 Application Flow

1. Messages are transmitted in real time via Socket.io  
2. Sentiment detection processes conversational tone  
3. The UI theme updates dynamically  
4. Messages are persisted in MongoDB  
5. Images are uploaded and optimized through Cloudinary  

---

## 🚀 Local Development Setup

### Requirements

- Node.js (v18 or higher)  
- MongoDB instance (local or Atlas)  
- Cloudinary account 

---

### Environment Variables

Create a `.env` file in the root directory:

```
MONGODB_URI=your_mongodb_connection_string
PORT=5001
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
NODE_ENV=development
```

---

### Installation Steps

Clone the repository:

```bash
git clone https://github.com/Sarthakmittal8/mesh-connect.git
cd mesh-connect
```

Install dependencies:

```bash
npm install
cd frontend && npm install
cd ../backend && npm install
```

Build the project:

```bash
npm run build
```

Start the server:

```bash
npm start
```

The application will run at:

```
http://localhost:5001
```

---

## 📱 Cross-Device Compatibility

Mesh Connect is engineered for adaptive layouts across devices:

- Desktop: Full messaging interface with complete feature set  
- Tablet: Balanced layout with responsive scaling  
- Mobile: Optimized UI for compact and on-the-go communication  

---

## 👨‍💻 Author

**Sarthak Mittal**  
Lead Developer & System Architect  

---

## 📄 License

This project is licensed under the MIT License.  
You are free to use, modify, and distribute this software in accordance with the terms of the license.
