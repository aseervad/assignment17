# 🗣️ IELTS Speaking Test Web App — Assignment 17

Welcome to **Assignment 17** – a full-stack IELTS Speaking Test platform that lets users **record, play back, and submit audio responses**, with a clean React frontend and a robust Flask backend.

This project showcases advanced use of the **MediaRecorder API**, **React Hooks**, and **Flask audio file handling** — all wrapped up in a seamless test-taking experience.

---

## 🚀 Features

✅ **Real-Time Audio Recording** using native browser Media API  
✅ **Playback & Re-record** functionality before submission  
✅ **Submit Audio + Text Response** to Flask backend  
✅ **Automatic File Storage** and secure backend upload handling  
✅ **Instant Feedback & Confirmation UI**  
✅ **Audio Player + Download Link** shown after submission  
✅ **Responsive, Accessible, Clean UI**  
✅ **Error Handling** for microphone denial, network issues, etc.

---

## 📸 Screenshots

### 🎤 Recording Response  
![Recording](./screenshots/recording.png)

### ✅ Submitted with Audio Preview  
![Submitted](./screenshots/submitted.png)

---

## 🧱 Tech Stack

### Frontend:
- ⚛️ React (with Hooks)
- 🎙️ MediaRecorder API
- 💅 Custom CSS
- 📦 Axios

### Backend:
- 🐍 Python + Flask
- 🔧 Flask-CORS, Flask-Migrate
- 🗃️ SQLite (via SQLAlchemy)
- 🎙️ File handling with `werkzeug` & `uuid`

---

## 🛠️ Setup Instructions

### 📦 Install Frontend

```bash
cd assignment17/ielts-speaking-test
npm install
npm start
