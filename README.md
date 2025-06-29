FOURFRAME Frontend
FOURFRAME is a sleek, responsive single-page application built with React, featuring JWT authentication, user profiles (with profile picture upload), and dynamic interactions through secure frontend logic.

 Live Demo
Frontend Live on Vercel:https://fourframe-fronted.vercel.app/

 Project Overview
This is the frontend of the FOURFRAME full-stack application, developed to demonstrate:

JWT-based authentication

SPA routing with React Router

Responsive design using Tailwind CSS

Secure profile management (update name, email, and profile picture)

Clean and modular React architecture

 Features
 User Registration & Login
 JWT Authentication (stored in localStorage)
 Protected Routes
 Profile Page with Update Support
 Profile Picture Upload with Image Preview
 Error & Loading State Handling
 Responsive Design with Tailwind CSS
 Clean Component-Based Structure

 Screenshots
Profile Update Page with Image Upload


 Getting Started
 Prerequisites
Node.js (v16+ recommended)

npm or yarn

 Installation
bash
Copy
Edit
git clone git@github.com:Ourfullstackapp/FOURFRAME-FRONTED.git
cd FOURFRAME-frontend
npm install
⚙️ Environment Variables
Create a .env file in the root directory and configure necessary variables (e.g., API base URL):

bash
Copy
Edit
VITE_API_BASE_URL=http://localhost:5000/api
Running the App Locally
bash
Copy
Edit
npm run dev
App will be live at:
http://localhost:3000

Tech Stack
React – Frontend Framework

React Router – SPA Routing

Axios – HTTP Client

Style CSS – Styling

JWT – Auth Token Management

Vite – Development & Build Tool

Auth Flow (Frontend)
JWT stored in localStorage on login

Protected routes require a valid token

Token is sent in requests as Authorization: Bearer <token>

Invalid/expired tokens trigger logout

Testing
bash
Copy
Edit
npm run test
Includes one frontend test using React Testing Library for validating login flow.

Documentation
React Docs

Style CSS Docs

JWT Docs

Axios Docs

Contributors
Owen Kariuki

Tyra Mwai

License
This project is licensed under the MIT License.

