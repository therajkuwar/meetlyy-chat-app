# 🌍 Meetlyy - Language Exchange & Video Calling App

**Meetlyy** is a full-stack real-time communication platform designed to connect language learners. It allows users to find partners based on native and learning languages, chat in real-time, and hop on high-quality video calls to practice speaking.

Built with the **MERN Stack** (MongoDB, Express, React, Node.js) and powered by **GetStream.io** for robust chat and video capabilities.

## ✨ Key Features

* **🔐 Authentication & Onboarding**: Secure signup/login with profile setup for language preferences.
* **📹 Video Calls**: High-quality, low-latency video calling integrated via Stream Video SDK.
* **💬 Real-time Chat**: Instant messaging with channel support using Stream Chat.
* **🤝 Friend System**: Send, accept, and manage friend requests. View recommended users based on language compatibility.
* **🔔 Notifications**: Real-time alerts for new friend requests and connections.
* **🎨 Dynamic Theming**: Choose from 30+ themes (Light, Dark, Cyberpunk, Retro, Coffee, etc.) powered by DaisyUI and Zustand.
* **📱 Responsive Design**: Fully responsive UI built with Tailwind CSS.

## 🛠️ Tech Stack

### **Frontend**
* **React (Vite)**: Fast and modern UI library.
* **Tailwind CSS & DaisyUI**: Utility-first styling with pre-built accessible components.
* **TanStack Query**: Efficient server state management and data fetching.
* **Zustand**: Lightweight global state management for theming.
* **Stream SDKs**: `stream-chat-react` and `@stream-io/video-react-sdk` for communication features.
* **Lucide React**: Beautiful, consistent icons.

### **Backend**
* **Node.js & Express**: Robust REST API.
* **MongoDB**: NoSQL database for storing users and relationships.
* **JWT**: Secure stateless authentication.
* **Stream API**: Backend token generation for chat/video sessions.

## 🚀 Getting Started

Follow these steps to set up the project locally.

### Prerequisites
* Node.js (v18+)
* MongoDB (Local or Atlas)
* [GetStream.io](https://getstream.io/) Account (for API Key/Secret)

### 1. Clone the Repository
```bash
git clone [https://github.com/therajkuwar/meetlyy-chat-app.git](https://github.com/therajkuwar/meetlyy-chat-app.git)
cd meetlyy-chat-app.git
