# 🚀 AI-Powered Adaptive Quiz Agent

> **An intelligent learning system that converts any content into personalized, adaptive quizzes powered by AI.**

![Project Banner](public/banner1.jpeg)

---

## 🧠 Overview

The **AI-Powered Adaptive Quiz Agent** is a next-generation educational platform designed to revolutionize how users learn and assess knowledge.

Instead of static quizzes, this system leverages **AI to dynamically generate questions**, analyze user performance, and continuously adapt difficulty levels to maximize learning efficiency.

It transforms **passive content → active learning experience**.

---

## ✨ Core Features

### 📂 Multi-Source Quiz Generation

Generate quizzes instantly from diverse inputs:

* 📄 **PDF Documents** → Automatic content extraction & question generation
* 🎥 **YouTube Videos** → Transcript-based intelligent quizzes
* 🌐 **Web URLs** → Context-aware question creation
* 📝 **Custom Topics** → On-demand quiz generation

---

### 🧠 Adaptive Intelligence Engine

* Real-time performance tracking
* Dynamic difficulty adjustment
* Focused learning on weak areas
* Personalized question sequencing

---

### 📊 Advanced Analytics Dashboard

* Visual performance insights
* Topic-wise strength & weakness detection
* Progress tracking over time
* Data-driven learning recommendations

---

### 👥 Real-Time Collaborative Quiz System

* Multiplayer quiz rooms
* Live leaderboards
* Competitive & team-based learning
* Instant result synchronization using WebSockets

---

### 📝 AI-Generated Learning Paths

* Smart revision notes
* Personalized study recommendations
* Auto-generated summaries from mistakes
* Continuous improvement loop

---

### 🔐 Secure Authentication & User Management

* Seamless login/signup using Clerk
* Protected routes & session handling
* Scalable user system

---

### 🎨 Premium User Experience

* Fully responsive UI
* Smooth animations with Framer Motion
* Clean, modern design system
* Built using Shadcn UI + Tailwind CSS

---

## 🛠️ Tech Stack

| Layer                  | Technology                             |
| ---------------------- | -------------------------------------- |
| **Frontend**           | Next.js (App Router), React            |
| **AI Engine**          | Google Gemini AI + QWEN 3.5            |
| **Backend**            | Node.js, Server Actions                |
| **Database**           | MongoDB + Mongoose                     |
| **Authentication**     | Clerk                                  |
| **Styling**            | Tailwind CSS, Shadcn UI, Framer Motion |
| **Charts & Analytics** | Recharts                               |
| **Real-Time Engine**   | Socket.io                              |

---

## ⚙️ System Architecture (High-Level Flow)

```text
User Input (PDF / URL / Topic)
            ↓
   AI Processing Layer (Gemini / QWEN)
            ↓
   Quiz Generation Engine
            ↓
   User Interaction (Quiz Attempt)
            ↓
   Performance Analysis Engine
            ↓
   Adaptive Learning + Recommendations
```

---

## 🚦 Getting Started

### 📌 Prerequisites

* Node.js (v18+)
* MongoDB (Atlas or Local)
* Gemini API Key
* Clerk API Keys

---

### ⚡ Installation

#### 1. Clone Repository

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

#### 2. Install Dependencies

```bash
npm install
```

#### 3. Setup Environment Variables

```bash
cp .env.example .env.local
```

```env
DATABASE_URL=
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
GEMINI_API_KEYS=
QWEN_API_KEY=
```

---

#### 4. Run the Application

```bash
npm run dev
```

👉 Open: http://localhost:3000

---

## 📁 Project Structure

```text
├── src/
│   ├── app/            # Routing & API endpoints
│   ├── components/     # UI components
│   ├── lib/            # AI, DB, utilities
│   ├── models/         # Database schemas
│   ├── actions/        # Business logic
│   └── data/           # Static content
├── public/             # Assets (images, banner)
├── .env.example
├── package.json
└── README.md
```

---

## 🎯 Key Highlights

* ⚡ Converts **any content into quizzes instantly**
* 🧠 Uses **AI for adaptive learning**
* 📊 Provides **deep performance insights**
* 👥 Supports **real-time multiplayer quizzes**
* 📚 Generates **learning paths automatically**

---

## 🚀 Future Enhancements

* Voice-based quiz interaction 🎤
* AI tutor/chat assistant 🤖
* Mobile app version 📱
* Gamification (badges, streaks, rewards) 🏆

---

## 🤝 Contributing

Contributions are welcome!

```bash
1. Fork the repository
2. Create a new branch
3. Make your changes
4. Commit and push
5. Submit a Pull Request
```

---

## ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub!

---

## 🏁 Conclusion

This project demonstrates how **AI + Real-Time Systems + Modern Web Tech** can redefine digital learning experiences.

---

Developed with ❤️ for the **Agentica 2.0 Hackathon**
