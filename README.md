# 🚀 Kun AI - Voice AI Platform

**Kun AI** is a professional, full-stack AI platform designed for high-fidelity, character-based voice synthesis. Built with a robust **FastAPI** backend and a high-performance **React** frontend, it demonstrates modern AI integration, real-time audio processing, and a scalable demo access system.

---

## 🎥 Project Demo
[Insert Demo Video Link Here]

---

## 🖼️ Screenshots
| UI Overview | Character Select | Voice Call Interface |
| :---: | :---: | :---: |
| ![Home](https://via.placeholder.com/300x200?text=App+Home) | ![Characters](https://via.placeholder.com/300x200?text=Character+Select) | ![Chat](https://via.placeholder.com/300x200?text=Voice+Chat) |

---

## 🔗 Live Demo
Check out the platform in action:  
👉 **[Live Demo Link](https://your-frontend-vercel-link.app)**

---

## ✨ Features
*   **AI Voice Generation**: Real-time text-to-speech synthesis with low latency.
*   **Character-Based Personalities**: Unique, pre-configured AI personas with distinct voices and behaviors.
*   **Multilingual Support**: Optimized for English and Hinglish (Hindi-English blend) interactions.
*   **Secure Demo Access**: A custom-built system that provides unique, usage-limited access links for recruiters and testers.
*   **Interactive UI**: A modern, responsive interface built with Tailwind CSS and Framer Motion for smooth animations.

---

## 🛠️ Tech Stack
*   **Frontend**: React, Vite, Tailwind CSS, Lucide icons, Framer Motion.
*   **Backend**: FastAPI (Python), Uvicorn, Python-dotenv.
*   **AI & Audio**: 
    *   **TTS**: Edge-TTS (Performance-optimized) & Coqui XTTS v2 (Local high-fidelity).
    *   **STT**: OpenAI Whisper (Faster-Whisper implementation).
    *   **LLM**: Google Gemini API integration.
*   **Auth & Security**: JWT (JSON Web Tokens), BCrypt hashing, and custom Token-based Demo system.
*   **Database**: Persistent JSON storage for lightweight, portable deployment.

---

## 🔐 Demo Access System
To prevent service misuse and ensure fair access, Kun AI features a custom-engineered **Token-Based Demo Access System**:
*   **Unique Access Links**: Each user/recruiter receives a unique, secure demo link.
*   **Independent Sessions**: Users are logged in automatically via their unique token without needing a password.
*   **Usage Limiting**: Each demo session is capped (e.g., at 40 requests) to protect API resources and manage costs.
*   **Real-time Tracking**: Usage is tracked server-side and persists across sessions.

---

## ⚠️ Important Notes
*   **Cold Start**: Since the backend is hosted on Render's free tier, the first request may take **30–60 seconds** to wake up. Please be patient while the "Neural Link" syncs!
*   **TTS Performance**: The live demo is optimized with **Edge-TTS** for lightning-fast voice synthesis. High-fidelity local models (Coqui) are available in the full version.
*   **Data Persistence**: Note that user-created characters in the demo environment may reset periodically due to ephemeral storage on the free tier.

---

## 📌 Project Highlights
*   **High-Quality Architecture**: Modular, clean, and production-ready Python and React codebases.
*   **Real-world Scalability**: Designed to handle multiple independent demo users simultaneously.
*   **Full-stack Ownership**: Managed everything from STT/TTS processing pipelines to frontend state management.

---

## 📬 Contact / Access Request
**Notice**: The source code is withheld in this public repository for intellectual property protection.

I am more than happy to provide **full source code access** and a **private walkthrough** for recruiters and hiring managers. 

📩 **Connect with me**: [Your Email or LinkedIn]

---
© 2024-2026 Kun AI Platform. Designed & Developed by [Your Name].
