# Task Scheduler with Recurring Events

## 📌 Project Overview
This is a Task Scheduler application with recurring event support. It allows users to create, update, and manage tasks with recurring schedules.

## 🚀 Features
- Add, update, and delete tasks
- Recurring event support using `node-cron`
- Backend API with Express.js
- Frontend built with React.js
- Uses `axios` for API communication

## 📂 Folder Structure
```
Task-Scheduler-with-Recurring-Events/
│── backend/          # Backend server files
│    ├── cron/        # Cron jobs for scheduling
│    ├── db/          # Database files
│    ├── routes/      # API routes
│    ├── server.js    # Main backend server
│── public/           # Public assets
│── src/              # Frontend source code
│    ├── components/  # React components
│    ├── services/    # API services
│    ├── App.jsx      # Main React component
│    ├── index.jsx    # React entry point
│── package.json      # Project configuration
```

## 🛠️ Installation & Setup

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/your-repo/Task-Scheduler-with-Recurring-Events.git
cd Task-Scheduler-with-Recurring-Events
```

### 2️⃣ Install Dependencies
```bash
npm install
```

### 3️⃣ Install `concurrently` (If Missing)
```bash
npm install concurrently --save-dev
```

### 4️⃣ Start the Application
```bash
npm start
```
This will start both the frontend and backend simultaneously.

### 🔹 Manual Start (If Needed)
If `npm start` fails, start the backend and frontend separately:

#### **Start Backend**
```bash
cd backend
node server.js
```

#### **Start Frontend**
```bash
cd src
npm start
```

## 🖼️ Screenshot
![Image](https://github.com/user-attachments/assets/71e678d2-890c-4ab6-bc51-dc303b32ee37)

