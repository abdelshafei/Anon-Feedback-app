# 🕵️ Anonymous Feedback App

A full-stack web application that allows users to submit anonymous feedback to individuals or groups. Built with Angular, Node.js (or Python), and SQLite to help showcase our skills for co-op applications.

---

## 🚀 Features

- Submit anonymous feedback to a channel (person, group, or class)
- View all feedback posted to a channel
- Optional password-protected channels
- Admin moderation (delete or report feedback)
- Mark feedback as helpful (👍)
- Fully responsive frontend

---

## 🛠️ Tech Stack

- **Frontend:** Angular
- **Backend:** Node.js (Express) or Python (Flask/FastAPI)
- **Database:** SQLite
- **Deployment:** Netlify (frontend) + Render/Heroku (backend) *(optional)*

---

## 📁 Project Structure

/client → Angular frontend
/server → Backend API (Node.js or Python)
└── db/ → SQLite schema and helper functions
README.md


---

## 🧪 API Endpoints

| Method | Endpoint               | Description                       |
|--------|------------------------|-----------------------------------|
| POST   | `/api/feedback`        | Submit new anonymous feedback     |
| GET    | `/api/feedback/:id`    | Get feedback for a channel        |
| DELETE | `/api/feedback/:id`    | Delete feedback (admin only)      |
| PUT    | `/api/feedback/:id/upvote` | Mark feedback as helpful     |

---

## 👥 Roles & Responsibilities

### **Yousef**
- Backend setup (Express or Flask)
- SQLite schema (tables: `feedback`, `channels`, `reported`)
- API routes for submit, fetch, delete, upvote, report
- Admin route protections
- Deployment (backend)

### **Partner**
- Angular UI setup and routing
- Submit Feedback form
- View Feedback page (by channel)
- Admin Dashboard (view/delete/reported)
- Responsive styling + animations
- Deployment (frontend)

---

## ✅ To-Do List

- [ ] Set up repo and basic project structure
- [ ] Design database schema
- [ ] Create REST API endpoints
- [ ] Build feedback submission form
- [ ] Build feedback display page
- [ ] Add admin and moderation tools
- [ ] Final testing and deployment
- [ ] Write full documentation

---

## 📸 Screenshots

*(Add once UI is built)*

---

## 🧠 Future Features

- Email notifications for new feedback
- Auth system for admins
- CSV export
- Dark mode

---

## 📄 License

MIT License
