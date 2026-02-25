# 🌤️ ApsarWeather

![AvsarWeather Banner](https://your-image-link-here.com/banner.png)  

AvsarWeather is a **full-stack weather web application** that provides users with real-time weather updates, personalized dashboards, and the ability to save favorite cities. This project is built using **React**, **Tailwind CSS**, **Node.js**, **Express.js**, and **MongoDB Atlas**.  

---

## 🚀 Features

### **Geolocation-based Weather**
- On visiting the website, the user is prompted to allow geolocation.
- If the user agrees, ApsarWeather fetches the **current location's weather** instantly.
- Displays essential details like temperature, sunrise/sunset times, and other relevant weather information.

### **Navigation Bar**
- Three main buttons: **Home**, **Login**, and **Sign Up**.
- Home: Displays the current weather data.
- Login: Allows existing users to sign in.
- Sign Up: Allows new users to create an account.

### **User Authentication**
- Login only works for registered users.
- If the user enters an **invalid email or password**, an error message is shown.
- Sign up stores the user’s data securely in **MongoDB Atlas**.
- After successful login, the user is redirected to the **protected Dashboard**.

### **Protected Dashboard**
- Accessible **only after login**.
- Users cannot access the dashboard directly without authentication; they are redirected to login if not signed in.
- Dashboard shows:
  - **Current weather details**
  - **Sunrise and sunset times**
  - **Other important weather data**
- Users can **add favorite cities** to view them anytime.
- Favorite cities persist across sessions for logged-in users.

---

## 🛠️ Tech Stack

- **Frontend**: React, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB Atlas
- **Authentication**: JWT and protected routes
- **Weather API**: OpenWeatherMap

---

## ⚡ Pages

### Home Page
### Login Page
### Sign Up Page
### Dashboard

---

## 💻 Getting Started

### Prerequisites
- Node.js installed
- MongoDB Atlas account
- Weather API key for using a third-party API

### Installation
1. Clone the repository
2. Navigate to the project folder
3. Install backend dependencies
4. Install frontend dependencies
5. Create a .env file in backend directory
