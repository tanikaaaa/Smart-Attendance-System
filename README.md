# 📲 Smart Attendance System – QR Based

A full-stack web-based attendance management system that uses dynamic QR codes for fast, secure, and contactless attendance tracking.

The system supports three user roles — **Students, Teachers, and Administrators** — with dedicated dashboards and role-based access control.

---

## 🚀 Overview

Smart Attendance System replaces manual roll calls with QR-based verification.

Teachers generate session-specific QR codes, and students scan them to mark attendance instantly. Attendance records are stored securely and can be monitored in real time.

The system ensures efficiency, prevents proxy attendance, and provides structured attendance reports.

---

## 🛠️ Tech Stack

### 🎨 Frontend
- React 19
- React Router DOM
- Vite
- Axios

### 🔧 Backend
- Node.js
- Express 5
- MongoDB
- Mongoose
- JWT Authentication
- QR Code Generation

---

## 🌟 Core Features

### 📲 QR-Based Attendance
- Teachers generate unique QR codes per session  
- Students scan QR codes to mark attendance  
- Session-based validation prevents misuse  

### 👥 Role-Based Access Control
- Separate dashboards for Students, Teachers, and Admins  
- Secure JWT-based authentication  

### 📊 Attendance Management
- Real-time attendance tracking  
- View attendance registers  
- Export attendance data to CSV  

### 🏫 Class & Session Management
- Teachers create and manage classes  
- Students join classes using class codes  
- Schedule sessions with start and end times  

### ⚡ Real-Time Updates
- Automatic refresh of attendance data  
- Instant session validation  

---

## ⚙️ Installation

### 1️⃣ Clone Repository

```bash
git clone <repository-url>
cd "SE Project"
```

---

### 2️⃣ Backend Setup

```bash
cd Se-project/backend
npm install
```

Create a `.env` file inside the `backend` folder:

```
MONGO_URI=mongodb://127.0.0.1:27017/smart-attendance
PORT=4000
JWT_SECRET=your-secret-key
```

---

### 3️⃣ Frontend Setup

```bash
cd ../frontend
npm install
```

---

## ▶️ Running the Application

### Start MongoDB
Make sure MongoDB is running locally.

### Start Backend

```bash
cd Se-project/backend
npm run dev
```

Backend runs on:
```
http://localhost:4000
```

### Start Frontend

```bash
cd Se-project/frontend
npm run dev
```

Frontend runs on:
```
http://localhost:5173
```

---

## 👨‍💻 How It Works

1. Teachers create a class  
2. Students join using class codes  
3. Teachers schedule a session  
4. System generates a unique QR code  
5. Students scan QR to mark attendance  
6. Attendance is stored with timestamp in MongoDB  

---

## 📂 Project Structure

```
SE Project/
├── Se-project/
│   ├── backend/
│   │   ├── models/
│   │   ├── routes/
│   │   ├── middleware/
│   │   └── server.js
│   │
│   └── frontend/
│       └── src/
│           ├── pages/
│           └── components/
```

---

## 🔌 API Routes

- `/api/auth/*` – Authentication (Login / Signup)
- `/api/classes/*` – Class Management
- `/api/sessions/*` – Session Scheduling
- `/api/attendance/*` – Attendance Tracking
- `/api/admin/*` – Administrative Controls

---

## 📸 Demo

![Attendance Register](Attendance-register.jpeg)
![Teacher Dashboard](Teacher-Dashboard.jpeg)

---

## 🎯 Problem It Solves

- Eliminates manual attendance sheets  
- Reduces proxy attendance  
- Saves classroom time  
- Provides structured digital records  
- Enables contactless verification  

---

## 🔮 Future Enhancements

- Deployment on cloud (Render / AWS / Vercel)  
- Email notifications for session start  
- Analytics dashboard with charts  
- Mobile app integration  
- QR expiration timer with dynamic regeneration  

## Demo
![Attendance Register](Attendance-register.jpeg)
![Teacher Dashboard](Teacher-Dashboard.jpeg)




