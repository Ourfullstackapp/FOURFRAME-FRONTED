# FOURFRAME Frontend

FOURFRAME is a sleek, responsive single-page application built with **React** , featuring **JWT authentication**, user profiles (with profile picture upload), and dynamic interaction with a Flask-based RESTful API.

## Live Demo

[Frontend Live on Vercel]

---

## Project Overview

This is the **frontend** of the FOURFRAME full-stack application, developed as part of a final project to demonstrate:

- JWT-based authentication
- SPA with React Router
- Responsive design using Tailwind CSS
- Integration with a Flask REST API
- Secure profile management (update name, email, and profile picture)

---

## Features

 User Registration & Login  
 JWT Authentication (stored in localStorage)  
 Protected Routes  
 Profile Page with Update Support  
 Profile Picture Upload (image preview included)  
 Error & Loading State Handling  
 Responsive Design using Tailwind  
 Clean, component-based architecture  

---

##  Screenshots

> Profile Update Page with Image Upload:
![Profile Page](./public/screenshot-profile.png)

---

##  Getting Started

### Prerequisites

- Node.js (v16+ recommended)
- npm or yarn

###  Installation

```bash
git clone https://github.com/yourusername/fourframe-frontend.git
cd fourframe-frontend
npm install
⚙️Environment Variables
Create a .env file in the root directory:

env
Copy
Edit
VITE_API_URL=http://localhost:5000/api
Replace with your deployed API URL when in production.

Running the App Locally
bash
Copy
Edit
npm run dev
The app will be available at http://localhost:3000

🛠️ Tech Stack
React – Frontend framework

React Router – SPA routing

Axios – HTTP requests

Tailwind CSS – Styling

JWT – Auth token management

Vite – Fast dev server & build tool


On login, JWT is received and stored in localStorage

Protected routes require valid token

Token is attached as Authorization: Bearer <token> in all API calls

Invalid or expired tokens are handled with automatic logout

Testing
bash
Copy
Edit
npm run test
Includes one front-end test using React Testing Library for login flow validation.

API Integration
All API calls are made to the Flask backend. Example:

js
Copy
Edit
axios.get('/profile', {
  headers: {
    Authorization: `Bearer ${token}`
  }
})
See Backend API Documentation for full endpoint reference.

Deployment
Frontend is deployed to Vercel

Backend is deployed to Render

Environment variables are managed securely

Documentation
React Docs
Tailwind CSS Docs
JWT Docs
Axios Docs

Contributors:
Owen Kariuki
Tyra Mwai

License
This project is licensed under the MIT License.










