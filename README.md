# 🏥 Doctor Appointment Booking System

A full-stack web application for booking and managing doctor appointments, built with **MongoDB**, **Express.js**, **React.js**, and **Node.js** (MERN stack). This platform allows patients to book appointments with doctors and lets doctors manage their schedules.

---

## 🚀 Features

- **Patient and Doctor Authentication** (JWT-based)
- **Doctor Profile Management**
- **Book / Cancel Appointments**
- **Admin Dashboard** 
- **Real-time Notifications** 
- **Responsive UI**

---

## 📁 Folder Structure---
-client

   
-config


-controllers


-middlewares


-models


-routes


-.env


-server.js


-README.md


---

## ⚙️ Prerequisites

Ensure you have the following installed:

- **Node.js** 
- **npm**
- **MongoDB** (local or MongoDB Atlas)

---

## 🛠️ Setup Instructions

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/doctor-appointment.git
cd doctor-appointment
```

2.Backend Setup (Node.js / Express)
```bash
cd doctor-appointment
npm install
```

Create .env File 
create a .env file and add the following configuration:
```bash
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
```
PORT: The port where your backend will run (default: 5000).


MONGO_URI: MongoDB connection string .


JWT_SECRET: A secret key for JWT token encryption.

3. Frontend Setup (React)
```bash
cd ../client
npm install
```
add following info. in .env file
```bash
VITE_API_URL=http://localhost:5000
```
This variable defines the API URL that frontend will use to make requests to the backend.


▶️ Running the Application
1. Start the Backend
Navigate to the doctor-appointment directory and run the backend:
```bash
cd doctor-appointment
node server.js
```
This will start the server on http://localhost:5000.

3. Start the Frontend
In a new terminal window, navigate to the client directory and run the frontend:
```bash
cd client
npm start
```
This will start the frontend on http://localhost:5173 (Vite default port).


🧩 Technologies Used


Frontend: React.js, React Router, Axios, Tailwind CSS / Bootstrap


Backend: Node.js, Express.js, Mongoose


Database: MongoDB


Authentication: JWT


State Management: Context API / Redux 


Notifications: webSockets


📦 Dependencies (Backend)

To install the backend dependencies, run the following command in directory:
```bash
npm install
```

Backend Dependencies:
```bash
express mongoose dotenv cors bcryptjs jsonwebtoken nodemon
```

express: Web framework for Node.js


mongoose: MongoDB ODM


dotenv: Loads environment variables


cors: Cross-origin resource sharing


bcryptjs: For hashing passwords


jsonwebtoken: For JWT-based authentication


nodemon: Automatically restarts the server on changes


📦 Dependencies (Frontend)


To install the frontend dependencies, run the following command in the client directory:
```bash
npm install
```


Frontend Dependencies:
```bash
axios react-router-dom
```

axios: For making HTTP requests to the backend


react-router-dom: For routing between pages
