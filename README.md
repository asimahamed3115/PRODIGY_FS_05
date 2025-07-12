# PRODIGY_FS_05

# 🌐 Task 05 – Social Media Web Application

This repository contains **Task 05** of the **Full Stack Web Development Internship** at **Prodigy InfoTech**.

## 📌 Task Overview

The goal of this task was to build a **Social Media Web Application** that mimics the core functionalities of a social networking platform. The app supports user authentication, post creation, likes, and a basic feed—allowing users to interact with each other’s content.

## ✨ Features

- 🔐 **User Authentication** (Sign Up / Sign In)
- 📝 **Create Posts** with text content
- ❤️ **Like** posts
- 📜 **View Feed** – shows all users' posts
- 🙍 **User Profiles** *(optional)*
- 📆 Timestamps for posts and actions

## 🛠️ Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB Atlas  
- **Authentication:** JWT & bcrypt  
- **Optional Add-ons:** Socket.io (for live updates), Multer (for image uploads)

## 📂 Folder Structure

/client           -> Frontend files /server /models         -> Mongoose schemas for Users and Posts /routes         -> Auth and post-related APIs /controllers    -> Logic handling server.js       -> Main server setup

## 🚀 How to Run Locally

1. **Clone the repository**
```bash
git clone https://github.com/your-username/PRODIGY_FSD_05.git

2. Navigate to the project



cd PRODIGY_FSD_05

3. Install backend dependencies



cd server
npm install

4. Set up .env file



PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

5. Start the backend server



node server.js

6. Open frontend Open index.html from /client folder in your browser, or use Live Server.




---

🎯 Learning Outcomes

Developed full stack CRUD features for social media interaction

Implemented secure user authentication with JWT

Created a basic feed system with real-time post updates

Strengthened RESTful API building and frontend-backend integration

Improved MongoDB schema design for user-post relationships



---

🔗 LinkedIn Post

Link to my LinkedIn post about this task


---

📃 License

This project is licensed under the MIT License.
