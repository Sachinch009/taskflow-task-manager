# TaskFlow - Full Stack Task Management Application

🚀 Live Demo: http://16.171.11.74

A modern full-stack task management application built using React, Node.js, Express.js, MongoDB Atlas, Docker, and AWS. The application enables users to manage daily tasks efficiently with authentication, task tracking, and task completion management.

---

## Features

### Authentication
* User Registration
* User Login
* JWT-based Authentication
* Protected Routes

### Task Management
* Create Tasks
* Edit Tasks
* Delete Tasks
* Mark Tasks as Completed
* Manage Pending Tasks
* Manage Completed Tasks

### User Experience
* Responsive Design
* Toast Notifications
* Modern UI
* Fast Navigation

---

## Tech Stack

### Frontend
* React.js
* Vite
* Axios
* React Router DOM
* Material UI

### Backend
* Node.js
* Express.js
* JWT Authentication
* Bcrypt
* REST API

### Database
* MongoDB Atlas
* Mongoose

### DevOps & Deployment
* Docker
* Docker Compose
* AWS EC2
* Git & GitHub

---

## Architecture
Frontend (React + Vite)
↓
Backend (Node.js + Express)
↓
MongoDB Atlas

---

## Project Structure

TaskFlow/
│
├── frontend/
│ ├── src/
│ ├── public/
│ ├── Dockerfile
│ └── package.json
│
├── backend/
│ ├── controllers/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── config/
│ ├── Dockerfile
│ ├── .dockerignore
│ └── server.js
│
├── docker-compose.yml
├── README.md
└── .gitignore

---

## Local Installation
### Clone Repository

```bash
git clone https://github.com/Sachinch009/taskflow-task-manager.git
cd taskflow-task-manager
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup
```bash
cd frontend
npm install
npm run dev
```

---

## Environment Variables

Create a .env file inside backend directory.

```env
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
```

## Docker Setup
### Build and Run

```bash
docker compose up --build
```

### Application URLs

Frontend:
http://localhost:5173

Backend:
http://localhost:4000

### Stop Containers

```bash
docker compose down
```

---

## Deployment

Application deployed on AWS EC2.

Production URL:

http://16.171.11.74

---

## API Endpoints
### Authentication
POST /api/user/register
POST /api/user/login

### Tasks
GET /api/tasks
POST /api/tasks
PUT /api/tasks/:id
DELETE /api/tasks/:id

---

## Future Improvements
* Email Verification
* Password Reset
* Task Categories
* Task Priority Levels
* Due Date Notifications
* Team Collaboration Features

---

## Author
Sachin Chaudhary

GitHub:
https://github.com/Sachinch009

---

## License
This project is developed for educational, learning, and portfolio purposes.
