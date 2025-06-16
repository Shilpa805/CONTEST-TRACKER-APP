# 🏆 CONTEST TRACKER

A **MERN-based web app** to track **upcoming and past coding contests** from **LeetCode, Codeforces, and CodeChef**.

---

## 🌐 Live Project

- 🔸 **Frontend (Vercel)**: [https://contest-tracker-app-lime.vercel.app](https://contest-tracker-app-lime.vercel.app)  
- 🔹 **Backend API (Render)**: [https://contest-tracker-app-backend.onrender.com](https://contest-tracker-app-backend.onrender.com)  
  _(Note: Only serves API routes like `/api/contests`, `/api/health`)_ 
- 🗂️ **GitHub Repo**: [https://github.com/Shilpa805/CONTEST-TRACKER-APP](https://github.com/Shilpa805/CONTEST-TRACKER-APP)

---

## 🚀 Features

✅ View **Upcoming**, **Past**, and **Today’s** contests  
✅ Filter contests by **platform** (LeetCode, Codeforces, CodeChef)  
✅ **Bookmark** your favorite contests using localStorage  
✅ **Add YouTube solution links** to past contests  
✅ **Dark/Light Mode toggle**  
✅ **Responsive** design built with **TailwindCSS**  
✅ **Cron jobs** auto-fetch latest contests daily  

---

## 🛠️ Tech Stack

- **Frontend**: React, Vite, TailwindCSS, React Router  
- **Backend**: Node.js, Express.js  
- **Database**: MongoDB (Mongoose)  
- **APIs**: Codeforces API, LeetCode GraphQL, CodeChef  
- **Cron Jobs**: node-cron + axios  
- **Deployment**: Vercel (Frontend), Render (Backend)

---

## ⚙️ Installation & Setup (Local)

### 🔧 Backend Setup

```bash
git clone https://github.com/Shilpa805/CONTEST-TRACKER-APP.git
cd CONTEST-TRACKER-APP/backend
npm install
```

### 📂 Folder Structure
```
contest-tracker/
├── backend/       # Express.js + MongoDB backend
│   ├── routes/
│   ├── models/
│   ├── utils/
│   └── server.js
│
├── frontend/      # React frontend with Vite + TailwindCSS
│   ├── src/
│   ├── public/
│   └── vite.config.js
│
└── README.md
```

### 👩‍💻 Author
```
Shilpa Kumari
📌 GitHub: @Shilpa805
```

🔥 **Happy Coding! 🚀**
