# ViNotes
Vi-Notes is an authenticity verification platform that analyzes keystroke dynamics, typing patterns, and behavioral signals to distinguish human-written content from AI-generated text.
# Vi-Notes ✍️

Vi-Notes is an authenticity verification platform designed to distinguish human-written content from AI-generated or AI-assisted text. It achieves this by analyzing real-time typing behavior, keystroke dynamics, and writing patterns.

## 🚀 Overview

The system captures how users write — not just what they write. By monitoring typing rhythm, pauses, corrections, and paste activity, Vi-Notes builds a behavioral signature that reflects natural human thinking patterns.

## 🔑 Key Features

- ✍️ Distraction-free writing editor  
- ⌨️ Keystroke dynamics tracking (latency & hold time)  
- 📋 Paste detection for suspicious input  
- 📊 Real-time behavioral insights visualization  
- 💾 Session storage using MongoDB  
- 🔐 (Optional) User authentication system  

## 🧠 How It Works

- Captures typing speed and timing variations  
- Detects micro-pauses and corrections  
- Flags pasted content instantly  
- Compares behavioral patterns with statistical signals  

Human writing typically shows:
- Irregular timing patterns  
- Frequent corrections  
- Variable typing speed  

AI-generated or pasted text often lacks these characteristics.

## 🛠️ Tech Stack

- **Frontend:** React  
- **Backend:** Node.js, Express  
- **Database:** MongoDB  
- **Libraries:** Axios  

## ⚙️ Setup Instructions

### Backend
```bash
cd backend
npm install
node server.js
cd frontend
npm install
npm start

