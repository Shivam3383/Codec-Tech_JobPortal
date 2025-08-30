# Codec-Tech_JobPortal
Job Portal

A full-stack job portal application built with React (Vite) for the frontend and Node.js + Express + MongoDB for the backend.

🚀 Features

User authentication (Signup/Login with JWT)

Role-based access (Student / Recruiter)

Job posting & job search functionality

Responsive UI with Tailwind CSS

REST API with Express & MongoDB

📂 Project Structure
job-portal/
│── backend/         # Express + MongoDB API
│   ├── index.js
│   ├── routes/
│   ├── models/
│   ├── middlewares/
│   └── .env
│
│── frontend/        # React (Vite) frontend
│   ├── src/
│   ├── public/
│   ├── package.json
│   └── vite.config.js
│
└── README.md

⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/your-username/job-portal.git
cd job-portal

2️⃣ Backend Setup
cd backend
npm install
npm run dev


Create a .env file in backend/ with:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

3️⃣ Frontend Setup
cd frontend
npm install
npm run dev


Frontend runs at 👉 http://localhost:5173
Backend runs at 👉 http://localhost:5000

📦 Build for Deployment (Frontend)
cd frontend
npm run build


This generates a dist/ folder.

For Netlify Deployment:

Build Command: npm run build

Publish Directory: dist

🌐 Deployment

Frontend → Netlify

🛠 Tech Stack

Frontend: React, Vite, Tailwind CSS, React Router, Radix UI

Backend: Node.js, Express.js, MongoDB, JWT, bcrypt

Deployment: Netlify (frontend)
https://jobportal-shivam312006.netlify.app/


