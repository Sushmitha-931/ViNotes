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
# 🚀 React + Vite + TypeScript Project

This is a modern web application built using React, Vite, and TypeScript.

---

## 📦 Prerequisites

Make sure you have the following installed:

- Node.js (LTS recommended)
- npm (comes with Node.js)

Check installation:

node -v
npm -v

---

## 📁 Getting Started

### 1. Clone the Repository

git clone https://github.com/your-username/your-repo.git
cd your-repo

Or download the ZIP file and extract it.

---

### 2. Install Dependencies

Make sure you are inside the project folder (where package.json exists), then run:

npm install

---

### 3. Run the Development Server

npm run dev

---

### 4. Open in Browser

After running the above command, you will see output like:

Local: http://localhost:5173/

Open that link in your browser.

---

## 🔐 Environment Variables

If the project requires environment variables:

1. Copy the example file:

cp .env.example .env

2. Open .env and add the required values.

---

## 🏗️ Build for Production

To create a production build:

npm run build

To preview the build:

npm run preview

---

## 📁 Project Structure

project-root/
├── src/                # Source code
├── public/             # Static files
├── package.json        # Dependencies & scripts
├── vite.config.ts      # Vite configuration
├── .env.example        # Environment template
└── README.md           # Documentation

---

## ❗ Common Issues & Fixes

### package.json not found
Make sure you are inside the correct project folder.

### Port already in use
npm run dev -- --port 3000

### Dependencies not installed
npm install

### Environment errors
Ensure .env file is created and properly configured.

---

## 🧑‍💻 Tech Stack

- React
- TypeScript
- Vite
- Node.js

---

## 📌 Notes

- Always run commands inside the project folder
- Do not modify core config files unless needed
- Ensure Node.js is properly installed

---

## 📜 License

This project is open-source and available under the MIT License.


