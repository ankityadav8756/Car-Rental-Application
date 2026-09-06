# 🚗 Car Rental Application

A full-stack Car Rental Web Application that allows users to browse available cars, view car details, and book cars. The application consists of a React frontend and a Node.js/Express backend connected to MongoDB.


## 📌 Project Overview

The Car Rental Application is designed to provide a simple and user-friendly platform for renting cars online.

Users can browse available cars, check car information, select rental dates, and make bookings.

The application follows a client-server architecture:

React Client → REST API → Node.js/Express Server → MongoDB

---

## ✨ Features

### 👤 User Features

- User registration and login
- User authentication
- Browse available cars
- View car details
- Select pickup and return dates
- Book a car
- View booking information
- Manage user profile

### 🚘 Car Features

- Display available cars
- Car details and specifications
- Car images
- Rental price
- Car availability

### 📅 Booking Features

- Create car bookings
- Select rental dates
- Calculate rental information
- View booking details
- Manage bookings

### 👨‍💼 Owner Features

- Owner authentication
- Add cars
- Manage cars
- View bookings
- Manage rental vehicles

---

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

---

## 📂 Project Structure

```text
Car-Rental-Application/
│
├── client/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── assets/
│   │   └── ...
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
