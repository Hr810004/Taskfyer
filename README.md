# ✅ Taskfyer – Effortless Task Management App

## 📌 Project Overview

Welcome to **Taskfyer**, your all-in-one productivity platform for managing tasks with ease. Taskfyer helps you organize, track, and complete your daily to-dos with a clean, modern interface. Whether you’re a student, professional, or anyone looking to boost productivity, Taskfyer is designed to keep you on top of your goals.

Hosted at: [https://taskfyer-tau.vercel.app/](https://taskfyer-tau.vercel.app/)

---

## 🌟 Key Features

- 📝 **Task Management** – Add, edit, and delete tasks with intuitive controls.
- 📅 **Task Status Tracking** – View tasks by status: All, Completed, Pending, and Overdue.
- 🔔 **Reminders & Notifications** – Never miss a deadline with timely reminders.
- 📊 **Progress Analytics** – Visualize your productivity with charts and stats.
- 🔒 **Secure Authentication** – Register and log in to keep your tasks private and secure.
- 🌙 **Modern UI/UX** – Beautiful, responsive design with TailwindCSS and custom components.

---

## 🛠️ Tools & Technologies

- **Next.js**: Modern React framework for full-stack web apps
- **React**: Fast, interactive UIs
- **Node.js & Express**: Robust backend API
- **MongoDB**: Scalable NoSQL database for storing tasks and users
- **JWT**: Secure authentication and session management
- **TailwindCSS**: Utility-first CSS for rapid UI development
- **Chart.js / Recharts**: Data visualization for analytics
- **Nodemailer**: Email notifications for reminders and verification

---

## 🚦 Getting Started

### 1. Set Up Environment Variables

Create a `.env` file in both the `backend/` and `client/` directories as needed. Example for backend:

```env
MONGO_URI=
JWT_SECRET=
EMAIL_USER=
EMAIL_PASS=
CLIENT_URL=http://localhost:3000
```

### 2. Install Dependencies

For both backend and client, run:

```bash
cd backend
npm install

cd ../client
npm install
```

### 3. Run the Application

Start the backend server:

```bash
cd backend
npm run dev
```

Start the frontend (client):

```bash
cd client
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) to access Taskfyer.

---

## 🌐 Deployment

### 1. Add Environment Variables
Add the `.env` variables to your hosting platform (e.g., Vercel for frontend, Railway/Render for backend).

### 2. Deploy
Deploy your app using your preferred method. For Vercel, connect your repo and set the environment variables.

---

## 🙌 Credits

Built by [Harsh810](https://harsh810.vercel.app) – Inspired by modern productivity and task management tools.

---
