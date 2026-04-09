# AppDesk — Application Support Platform

A full-featured React app for ticket management, SLA monitoring, and team escalation workflows.

---

## 🚀 How to Run in VS Code

### Prerequisites
Make sure you have these installed:
- **Node.js** (v16 or higher) → https://nodejs.org
- **VS Code** → https://code.visualstudio.com

---

### Step 1 — Open the Project in VS Code
1. Open **VS Code**
2. Click **File → Open Folder**
3. Select the `appdesk-react` folder → click **Open**

---

### Step 2 — Open the Terminal in VS Code
- Press **Ctrl + `** (backtick) on Windows/Linux
- Press **Cmd + `** on Mac
- Or go to **Terminal → New Terminal** from the menu

---

### Step 3 — Install Dependencies
In the terminal, type:
```
npm install
```
Wait for it to finish (may take 1–2 minutes).

---

### Step 4 — Start the App
```
npm start
```
The app will open automatically in your browser at:
**http://localhost:3000**

---

## 🔑 Demo Login
| Email | Password |
|-------|----------|
| admin@appdesk.com | admin123 |
| rahul@appdesk.com | rahul123 |
| priya@appdesk.com | priya123 |

---

## 📁 Project Structure
```
appdesk-react/
├── public/
│   └── index.html       ← HTML entry point
├── src/
│   ├── index.js         ← React entry point
│   └── App.jsx          ← Main application (all components)
├── package.json         ← Dependencies & scripts
└── README.md            ← This file
```

---

## ✨ Features
- 🔐 Login / Register / SSO
- 📋 Ticket list with search & filters
- 📊 Live stats (Open, In Progress, Escalated, Resolved)
- 🗂️ Ticket detail panel with timeline
- ➕ Create new tickets
- 🔄 Status changes & comments
- 📉 SLA progress bars
