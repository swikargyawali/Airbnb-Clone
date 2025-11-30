Wanderlust 🌍

A full-stack, production-ready clone of Airbnb with authentication, listings, search & filters, bookings, and a modern responsive UI.

🚀 Overview

Wanderlust is a complete end-to-end Airbnb-style application built to strengthen full-stack development skills.
It includes user authentication, property management, booking systems, responsive UI, and real-time functionality.

This project demonstrates skills in:

Backend development

RESTful API design

Database modeling

Authentication & security

Frontend integration

Clean, scalable architecture

✨ Features
🔐 Authentication & User System

Secure login & signup

Password hashing (bcrypt)

Session / JWT-based authentication

🏠 Listings

Create, edit, and delete property listings

Upload images (Cloudinary / Firebase)

Set price, location, amenities

Fully validated forms

🔎 Search & Filters

Search by location, date, and number of guests

Category-based filtering

Real-time search updates

📅 Booking System

Book listings with date range

Prevent overlapping bookings

User booking history

⭐ User Dashboard

Manage your listings

Manage your bookings

View personal activity

🛠️ Tech Stack
Frontend

React / Next.js (or React Native for mobile)

TailwindCSS / CSS Modules

Axios / Fetch API

Backend

Node.js

Express.js

REST API architecture

Database

MongoDB + Mongoose

Other Tools

Cloudinary / Firebase storage for images

JWT / Sessions for authentication

Git & GitHub for version control

📁 Project Structure (Basic)
Wanderlust/
│── public/          → static files (CSS, images, fonts)
│── views/           → EJS templates or React pages
│── routes/          → Express routes
│── controllers/     → Route logic
│── models/          → Mongoose schemas
│── middleware/      → Auth, validations, error handling
│── utils/           → Helper functions (email, date, etc.)
│── app.js           → Entry point / server setup
│── package.json
│── .env             → Environment variables