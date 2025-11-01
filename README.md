# LeadHer
🩷 LeadHer — Empowering Women Through a Connected Platform
🚀 Overview

LeadHer is a web platform designed to empower women by providing a secure and supportive space for networking, personal growth, and entrepreneurship.
The project is built using the MERN stack (MongoDB, Express, React, Node.js) and includes user authentication (Register/Login) as its foundation.

✨ Features

✅ User Registration & Login — Secure authentication using JWT and bcrypt.
✅ MongoDB Integration — All user data stored safely in a NoSQL database.
✅ Responsive UI — Built with React for a modern and smooth experience.
✅ Backend API — Node.js + Express server handles routes and logic.
✅ Error Handling — Frontend and backend validation for user input.
✅ Scalable Structure — Ready for new features like dashboards, mentorship, or community spaces.

🧠 Tech Stack
Layer	Technology
Frontend	React.js, React Router, Axios, CSS
Backend	Node.js, Express.js
Database	MongoDB, Mongoose
Authentication	JWT, bcrypt
Tools	Visual Studio Code, Postman, MongoDB Compass
⚙️ Setup Instructions
1️⃣ Clone the repository
git clone https://github.com/<your-username>/LeadHer.git
cd LeadHer

2️⃣ Install dependencies

Backend:

cd server
npm install


Frontend:

cd ../client
npm install

3️⃣ Configure environment variables

Create a .env file inside the /server directory:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
PORT=5000

4️⃣ Run the application

Open two terminals:

Backend

cd server
npm start


Frontend

cd client
npm start


Then visit 👉 http://localhost:3000

🗂 Folder Structure
LeadHer/
│
├── client/            # React frontend
│   ├── src/
│   │   ├── components/
│   │   │   ├── Login.js
│   │   │   ├── Register.js
│   │   │   ├── Auth.css
│   │   └── App.js
│   └── package.json
│
├── server/            # Express backend
│   ├── models/
│   │   └── User.js
│   ├── routes/
│   │   └── auth.js
│   ├── server.js
│   └── package.json
│
└── README.md

🌟 Future Enhancements

🔹 User Profiles with skill tags & achievements
🔹 Community Forum / Mentorship System
🔹 Blog or Resource Hub for Women Entrepreneurs
🔹 Chat Support / AI-powered career guide

💬 Author

👩‍💻 Sreya Govindaraj
Passionate about women empowerment, web development, and social innovation.
📧 You can add your contact or portfolio link here.

🛡 License

This project is licensed under the MIT License — you’re free to modify and share it with attribution.
