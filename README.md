# ✍️ Vi-Notes

Vi-Notes is an authenticity verification platform that analyzes keystroke dynamics, typing patterns, and behavioral signals to distinguish human-written content from AI-generated text.

---

## 🚀 Overview

Vi-Notes focuses on *how* users write rather than just *what* they write.

By monitoring typing rhythm, pauses, corrections, and paste activity, the system builds a behavioral signature that reflects natural human thinking patterns.

---

## 🔑 Key Features

- ✍️ Distraction-free writing editor  
- ⌨️ Keystroke dynamics tracking (latency & hold time)  
- 📋 Paste detection  
- 📊 Behavioral insights visualization  
- 💾 Session storage  
- 🔐 Optional authentication  

---

## 🧠 How It Works

- Captures typing speed and timing variations  
- Detects pauses and corrections  
- Flags pasted content  
- Analyzes behavior patterns  

### Human writing:
- Irregular timing  
- Frequent corrections  
- Natural pauses  

### AI / pasted content:
- Uniform timing  
- Minimal corrections  
- Instant text input  

---

## 🛠️ Tech Stack

- Frontend: React (Create React App)  
- Backend: Node.js + Express  
- Database: MongoDB  
- Libraries: Axios  

---

## 📦 Prerequisites

Make sure you have installed:

- Node.js (LTS recommended)  
- npm  

Check:

node -v  
npm -v  

---

## 📁 Project Structure

project-root/  
├── frontend/   # React app  
├── backend/    # Node.js server  
├── README.md  

---

## 🚀 How to Run the Project

### 1. Clone Repository

git clone https://github.com/your-username/your-repo.git  
cd your-repo  

---

## ▶️ Run Frontend

cd frontend  
npm install  
npm start  

Frontend runs on:
http://localhost:3000  

---

## ▶️ Run Backend

Open a new terminal:

cd backend  
npm install  
npm start  

Backend typically runs on:
http://localhost:5000  

---

## 🔐 Environment Variables

If required:

- Check `.env.example` in frontend/backend  
- Create `.env` file  
- Add required values  

---

## ❗ Common Issues

### Blank white screen
- Check browser console (F12)  
- Ensure backend is running  
- Check API URLs  

---

### Port already in use
Frontend:
npm start -- --port 3001  

Backend:
Change port in server file  

---

### Dependencies error
npm install  

---

### API not working
- Ensure backend is running  
- Check API URL (localhost:5000)  

---

## 📌 Notes

- Run frontend and backend in separate terminals  
- Always run commands inside respective folders  
- Do not delete `.env.example`  

---

## 📜 License

This project is open-source and available under the MIT License.
