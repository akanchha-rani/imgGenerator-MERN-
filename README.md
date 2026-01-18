## 🖼️ AI Image Generator – MERN Stack

A full-stack AI Image Generator web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
This application allows users to generate AI-powered images from text prompts using the OpenAI Image Generation API.

The project demonstrates full-stack development, API integration, secure backend handling, and a modern responsive frontend UI.

## 📸 Demo Preview
<img width="1429" alt="Screenshot 2024-12-08 at 7 06 27 PM" src="https://github.com/user-attachments/assets/afc30fc3-2f77-4574-b71e-9310435a0b5e">

## ✨ Key Features

🔮 AI-based Image Generation using OpenAI

📝 Text-to-Image generation from user prompts

👤 User name input displayed with generated results

⚡ Fast and responsive UI built with React + Vite

🔐 Secure backend API (API key hidden from frontend)

🧩 Clean MERN architecture

📱 Fully responsive design

🛠️ Easy to extend (image history, downloads, authentication)

## 🧠 Use Case

This project can be used as:

An AI tool demo

A portfolio full-stack project

A base for SaaS AI applications

A learning project for MERN + OpenAI API integration

## 🧱 Tech Stack

### Frontend

React.js

Vite

Tailwind CSS

Axios (API calls)

### Backend

Node.js

Express.js

OpenAI SDK

### Database

MongoDB (for future image storage / user data)

### Tools & Utilities

Git & GitHub

dotenv

Nodemon

🗂️ Project Structure
imgGenerator-MERN-/
│
├── server/                     # Backend (Node + Express)
│   ├── routes/                 # API routes
│   ├── controllers/            # Business logic
│   ├── models/                 # MongoDB schemas
│   ├── config/                 # DB & API configuration
│   ├── index.js                # Server entry point
│
├── src/                        # Frontend (React)
│   ├── components/             # Reusable UI components
│   ├── pages/                  # Page-level components
│   ├── assets/                 # Images & static assets
│   ├── App.jsx
│   └── main.jsx
│
├── public/
├── .env.example
├── package.json
├── vite.config.js
├── tailwind.config.js
└── README.md

🔄 Application Workflow

User enters a text prompt and name

Frontend sends request to backend API

Backend securely calls OpenAI Image Generation API

Generated image URL is returned

Image is rendered dynamically on the UI

🔐 Security Considerations

OpenAI API key is never exposed to the frontend

All requests are handled securely via backend

Environment variables protected using dotenv

🚀 Future Enhancements

🗃️ Save generated images to MongoDB

⬇️ Image download option

👥 User authentication (JWT)

❤️ Like / favorite images

🧾 Prompt history tracking
