# Bookstore Web Application

A full-stack MERN (MongoDB, Express.js, React.js, Node.js) based bookstore web application that allows users to browse, search, and manage a catalog of books. This project was originally forked to understand the MERN stack deeply and expand it with additional features like authentication, user profiles, and personalized browsing.

## Overview

This application provides a modern and interactive platform for book lovers. Users can register, log in securely, and explore a wide collection of books with detailed descriptions. The frontend is built with React and the backend is handled via Node.js and Express, with MongoDB as the database.

## Why I Built This

I forked the original repository to:
- Learn the MERN stack hands-on.
- Understand real-world full-stack architecture.
- Practice backend API development and frontend integration.
- Enhance features and personalize the experience.

## Features

- User registration and login with JWT-based authentication.
- Explore books with detailed information (title, author, description, etc.).
- Responsive UI for seamless experience across devices.
- Users can manage their own profile.
- Clean RESTful API architecture.

## Tech Stack

- Frontend: React.js, CSS
- Backend: Node.js, Express.js
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- Tools: Postman, Git, GitHub

## Project Structure

├── backend/  
│   ├── controllers/  
│   ├── models/  
│   ├── routes/  
│   ├── server.js  
│   └── config/  
├── frontend/  
│   ├── src/  
│   │   ├── components/  
│   │   ├── pages/  
│   │   └── App.js  
│   └── public/  
├── .env  
├── package.json  
└── README.md  

## Getting Started

1. Clone the repository

   git clone https://github.com/safibaig03/bookstore.git  
   cd bookstore

2. Install frontend dependencies

   cd frontend  
   npm install

3. Install backend dependencies

   cd ../backend  
   npm install

4. Set up .env in backend folder

   MONGO_URI=your_mongodb_connection_string  
   JWT_SECRET=your_jwt_secret  
   PORT=5000

5. Run the app

   In one terminal:  
   cd backend  
   npm start

   In another terminal:  
   cd frontend  
   npm start

6. Open http://localhost:3000 in your browser.

## Sample Screens

(Add screenshots here for home page, login page, and book details)


## Connect with Me

Mirza Safiulla Baig  
Email: safiullabaig786@gmail.com  
LinkedIn: https://linkedin.com/in/safibaig03  
GitHub: https://github.com/safibaig03
