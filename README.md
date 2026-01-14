# 🤖 AI-Powered Interview Assistant

An intelligent mock interview platform that simulates real-world interview scenarios using **voice-based interaction, live camera monitoring, and generative AI-driven evaluation**. The system helps candidates practice interviews in a realistic environment and receive instant AI feedback.

---

## 📌 Problem Statement

Interview preparation is often limited to text-based question–answer platforms, which fail to replicate the **real interview experience** involving verbal communication, confidence, and presence. Candidates struggle to practice speaking answers aloud and facing an interviewer-like environment.

---

## 💡 Solution

The **AI-Powered Interview Assistant** addresses this problem by conducting **verbal, camera-enabled mock interviews**.  
The AI acts as an interviewer by asking spoken questions, while the user answers verbally on camera. Responses are transcribed, evaluated using generative AI, and scored with detailed feedback.

---

## 🚀 Features

- 🎤 **Voice-Based Interview Questions** (AI speaks questions aloud)
- 🗣️ **Speech-to-Text Answer Capture**
- 📷 **Live Camera-Enabled Interview Environment**
- 🧠 **AI-Generated Interview Questions**
- 📊 **AI-Based Answer Evaluation & Scoring**
- 🧩 **Modular Interviewer & Interviewee Architecture**
- ⚡ **Real-Time Feedback and Summary**

---

## 🧠 System Architecture

The application is divided into two main modules:

### 👨‍💼 Interviewer Module
- Generates interview questions using Generative AI
- Verbally presents questions using text-to-speech
- Evaluates responses and provides feedback

### 👤 Interviewee Module
- Enables live camera and microphone access
- Captures spoken answers using speech recognition
- Displays transcribed responses in real time

---

## 🛠️ Tech Stack

### Frontend
- React
- Vite
- Tailwind CSS
- Redux Toolkit

### Backend
- Node.js
- Express.js

### AI & Media
- Google Gemini API (Question generation & evaluation)
- Web Speech API (SpeechRecognition & SpeechSynthesis)
- WebRTC (Camera & microphone access)

---

## 📂 Project Structure

