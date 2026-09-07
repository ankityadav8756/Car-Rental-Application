# 🚗 Car Rental Application

A full-stack Car Rental Web Application that allows users to browse cars, view car details, check availability, and book vehicles online. The application provides separate functionality for users and car owners.

## 📌 Project Overview

This project is built using a client-server architecture where the React frontend communicates with a Node.js/Express backend through REST APIs. MongoDB is used to store user, car, and booking information.

### Application Flow

React Client → REST API → Node.js/Express Server → MongoDB

## ✨ Features

### 👤 User
- User registration and login
- User authentication
- Browse available cars
- View car details
- Select pickup and return dates
- Book cars
- View booking details

### 🚘 Car Owner
- Owner authentication
- Add rental cars
- Manage cars
- View bookings
- Manage available vehicles

### 📅 Booking
- Select rental dates
- Create car bookings
- View booking information
- Manage rental bookings

## 🛠️ Technologies Used

### Frontend
- React.js
- JavaScript
- HTML5
- CSS3
- React Router
- Axios
- Vite

### Backend
- Node.js
- Express.js
- REST API
- JWT Authentication
- bcrypt

### Database
- MongoDB
- Mongoose

### Tools
- Git
- GitHub
- VS Code
- Postman

## 📂 Project Structure

```text
Car-Rental-Application/
│
├── client/
│   ├── public/
│   ├── src/
│   ├── package.json
│   └── package-lock.json
│
├── server/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── middleware/
│   ├── server.js
│   ├── package.json
│   └── package-lock.json
│
├── .gitignore
└── README.md
