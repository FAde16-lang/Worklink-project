# Worklink-project
Hackathon project 1
 # 💼 WorkLink - Real-Time Collaboration Platform for Remote Teams

![WorkLink Banner](https://yourdomain.com/banner-image.png) <!-- Optional banner -->

## 🚀 Overview

*WorkLink* is a full-stack, real-time collaboration platform built from scratch without the use of no-code tools or AI-powered development assistants. It’s designed specifically for remote teams to streamline productivity through task management, real-time communication, document sharing, and lightweight gamification features.

This platform blends the minimalism of *Microsoft Teams* with the modern, vibrant aesthetics of *Discord*, featuring smooth transitions, light/dark mode switching, and a responsive layout optimized for both desktop and mobile users.

---

## 🔗 Live Demo

👉 [View WorkLink Online]https://lighthearted-kelpie-7ce99c.netlify.app/
📽️ [Demo Video](https://your-demo-video.com)

---

## 📌 Features

### ✅ Core Functionality

- 🔐 *Authentication & Authorization*  
  Email/password login, role-based access (Admin / Member)

- 💬 *Real-Time Messaging*  
  Socket.IO-powered chat with typing indicators and online status

- 🗂️ *Kanban Task Management*  
  Drag-and-drop task board with status tracking and due dates

- 📎 *File Upload & Sharing*  
  Secure document upload with download support (Cloudinary / Firebase)

- 🌗 *Light & Dark Mode Toggle*  
  Theme switcher with user preference persistence

- 🏆 *Gamification System*  
  XP tracking per user with a leaderboard (based on tasks/messages)

- 🧭 *Navigation & Transitions*  
  Sidebar navigation, smooth page transitions, and interactive UI

---

## 🎨 UI/UX

- UI inspired by *Microsoft Teams* layout and *Discord* color palette
- Soft shadows, smooth hover animations, responsive grid system
- Mobile-first design with collapsible sidebars and fixed top navigation

---

## 🛠️ Tech Stack

| Layer           | Technology                      |
|----------------|----------------------------------|
| *Frontend*    | React.js, TailwindCSS            |
| *Backend*     | Node.js, Express.js              |
| *Real-Time*   | Socket.IO                        |
| *Database*    | MongoDB / PostgreSQL (choose one)|
| *Storage*     | Firebase Storage / Cloudinary    |
| *Auth*        | JWT + Custom Middleware          |
| *Deployment*  | Vercel (Frontend), Render (Backend) |

---

## 📁 Folder Structure
[11:03 AM, 6/21/2025] Soma sharan: worklink/
├── client/ # React frontend
│ ├── components/
│ ├── pages/
│ └── utils/
├── server/ # Node + Express backend
│ ├── controllers/
│ ├── routes/
│ ├── models/
│ └── socket/
├── shared/ # Constants, schemas
├── .env
├── README.md
└── package.json

## ⚙️ Setup & Installation

### Prerequisites:
- Node.js v18+
- MongoDB Atlas / PostgreSQL
- Firebase/Cloudinary (for file upload)
- Vercel/Render accounts for deployment

### 1. Clone the Repo
```bash
git clone https://github.com/yourusername/worklink.git
cd worklink
2. Setup Backend
bash
Copy
Edit
cd server
npm install
# Add your .env file
npm run dev
3. Setup Frontend
bash
Copy
Edit
cd ../client
npm install
npm start
4. Environment Variables
/server/.env
ini
Copy
Edit
PORT=5000
JWT_SECRET=your_jwt_secret
MONGO_URI=your_mongodb_url
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
/client/.env
ini
Copy
Edit
REACT_APP_API_BASE_URL=http://localhost:5000
📈 Gamification Rules
Action	XP Gained
Send a message	+1 XP
Create a task	+2 XP
Complete a task	+5 XP
Help teammate	+3 XP

Leaderboard is refreshed on page reload using XP data stored in the database.
🧪 Testing
Unit tests: (if implemented)

End-to-end tests with Postman collection (if applicable)

Manual testing checklist available in /docs/test-checklist.md

📦 Future Improvements
✅ Live collaborative document editing (e.g., Yjs)

✅ Google Calendar integration

✅ Notifications via email or PWA push

✅ Mobile app using React Native
📜 License
This project is licensed under the MIT License.

🙌 Acknowledgements
Figma (for UI references)

Discord & Microsoft Teams (for design inspiration)

Socket.IO, TailwindCSS, and Cloudinary

yaml
Copy
Edit****
