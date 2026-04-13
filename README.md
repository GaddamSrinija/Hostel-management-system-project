# 🏨 Residential Hostel Management System

A full-stack MERN (MongoDB, Express, React, Node.js) application designed to simplify hostel administration.  
The system allows administrators to manage students, track attendance, and maintain hostel records efficiently through a modern web interface.

---

## 🚀 Live Demo

- 🌐 Frontend: https://residential-hostelmanagement.netlify.app  
- ⚙️ Backend API: https://residential-hostel-management.onrender.com  

---

## ✨ Features

- Student registration and management  
- Attendance tracking system  
- Admin dashboard for hostel administration  
- Secure authentication using JWT  
- Google OAuth login integration  
- RESTful API architecture  
- MongoDB Atlas cloud database  
- Responsive React frontend  
- Deployed using Netlify and Render  

---

## 🛠️ Tech Stack

| Category        | Technology                      |
|----------------|--------------------------------|
| Frontend       | React.js, React Router, Axios  |
| Backend        | Node.js, Express.js            |
| Database       | MongoDB Atlas                  |
| Authentication | JWT, Google OAuth              |
| Deployment     | Netlify, Render                |

---

## 📁 Project Structure

```bash
Hostel-Management
│
├── frontend
│   ├── public
│   ├── src
│   │   ├── components
│   │   ├── screens
│   │   ├── actions
│   │   ├── reducers
│   │   └── App.js
│   └── package.json
│
├── server
│   ├── config
│   │   └── mongoDBConfig.js
│   ├── routes
│   ├── models
│   ├── middleware
│   ├── controllers
│   ├── index.js
│   └── package.json
│
└── README.md
```
---

## 📦 Prerequisites

Ensure the following tools are installed:

- Node.js (version 16 or higher)
- npm
- Git
- MongoDB Atlas account

### ✅ Check installations

`node -v`  
`npm -v`

---

## 📥 Clone the Repository

`git clone https://github.com/GaddamSrinija/Hostel-management-system-project.git`  
`cd Hostel-Management`

---

## ⚙️  Setup 

### 📁 Navigate to Project folder

`cd Hostel-management-system-project`

### 📦 Install dependencies

`npm install`

### 📁 Navigate to frontend folder

`cd frontend`

### 📦 Install dependencies

`npm install`

### 📁 Navigate to server folder

`cd server` 

### 📦 Install dependencies

`npm install`


### 🔐 Create `.env` file in server

Path: `server/.env`

Add the following:

NODE_ENV=development

PORT=5000

MONGO_URI=your_mongodb_connection_string

JWT_SECRET=your_secret_key

FRONTEND_URL=http://localhost:3000

GOOGLE_CLIENT_ID=your_google_client_id


### 💡 Example MongoDB URI

`mongodb+srv://username:password@cluster.mongodb.net/test?retryWrites=true&w=majority`

---

## 🚀 Run Backend Server

Development mode: `npm run dev`  

Production mode: `npm start` 

Backend runs on: http://localhost:5000

---

## 🎨 Frontend Setup (React)

### 📁 Navigate to frontend folder

`cd frontend`

### 📦 Install dependencies

`npm install`

### 🔐 Create `.env` file

Path: `frontend/.env`

Add:

REACT_APP_API_URL=http://localhost:5000

REACT_APP_GOOGLE_CLIENT_ID=your_google_client_id


---

## 🚀 Run Frontend

`npm start`  

Frontend runs on: http://localhost:3000

---

## 📜 Available Scripts

### ⚙️ Backend Scripts

- `npm run dev` → Runs backend in development mode  
- `npm start` → Runs backend in production mode  
- `npm install` → Installs dependencies  

### 🎨 Frontend Scripts

- `npm start` → Starts React development server  
- `npm run build` → Builds production version  
- `npm test` → Runs test suite  

---

## 🔌 API Endpoints

### 👤 User Routes
- POST `/users/login`  
- POST `/users/register`  
- POST `/users/google-login`  

### 🎓 Student Routes
- GET `/student`  
- POST `/student`  
- PUT `/student/:id`  
- DELETE `/student/:id`  

### 📊 Attendance Routes
- GET `/attendance`  
- POST `/attendance`  

---

## 🚀 Deployment

### ⚙️ Backend (Render)

- Root Directory: `server`  
- Build Command: `npm install`  
- Start Command: `npm start`  

### 🌐 Frontend (Netlify)

- Base Directory: `frontend`  
- Build Command: `npm run build`  
- Publish Directory: `frontend/build`  

Create file: `frontend/public/_redirects`

Add:

/* /index.html 200


---

## 🌟 Contribution

Contributions are welcome!

1. Fork the repository  
2. Create a branch → `git checkout -b feature-name`  
3. Commit → `git commit -m "Added new feature"`  
4. Push → `git push origin feature-name`  
5. Create Pull Request  

---

## 🔮 Future Improvements

- Cloudinary image uploads  
- Email notifications  
- Role-based access control  
- Mobile UI improvements  
- Admin analytics dashboard  

---

## 👩‍💻 Authors

- Shyam Sundar 
- Gaddam Srinija  
 
