# TaskBoard — Team Task Management System

TaskBoard is a full-stack task management platform that allows users to create organizations, invite members, manage tasks, and control access using subscription-based plans.

---

## 🚀 Features
- Organization creation and member invitations
- Task creation, assignment, and status tracking (To-Do / In-Progress / Done)
- Role-based access control
- Subscription-based member limits using Clerk
- Secure authentication and authorization

---

## 🛠 Tech Stack
- **Backend:** FastAPI, Python
- **Frontend:** React.js, Tailwind CSS
- **Auth & Subscriptions:** Clerk
- **Database:** PostgreSQL / SQLite

---

## 📸 Screenshots

### Dashboard
![Dashboard](./screenshots/dashboard.png)

### Subscrition
![Tasks](./screenshots/subscription.png)

### Organization & Members
![Organization](./screenshots/organization.png)

---

## ⚙️ Setup Instructions

### Backend
```bash
cd backend
uv venv
uv sync
uvicorn main:app --reload
