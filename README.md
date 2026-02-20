# Nexus E-commerce 

A beautiful, modern, minimal e-commerce web application with a sleek dark-mode glassmorphism design. Built with a React.js (Vite) frontend and a Node.js (Express) backend.

## Features

- ✨ **Beautiful UI**: Modern glassmorphism aesthetics, fluid animations, and a responsive layout.
- 🔐 **Authentication**: Full user registration and login system secured with JWTs.
- 🛍️ **Product Browsing**: Clean, dynamic product listing with hover effects.
- 🛒 **Shopping Cart**: Add items, adjust quantities, view real-time total pricing, and remove items dynamically.
- ⚡ **Lightning Fast**: In-memory data storage for instant response times and easy local testing.

## Prerequisites

Ensure you have Node.js installed on your machine. You can download it from [nodejs.org](https://nodejs.org/).

---

## Getting Started

### 1. Start the Backend Server

The backend runs on **port 5000** and provides the REST APIs for authentication, products, and the shopping cart.

1. Open your terminal and navigate to the `backend` folder:
   ```bash
   cd c:\Users\kusha\OneDrive\Desktop\E-commerece\backend
   ```
2. Install the backend dependencies:
   ```bash
   npm install
   ```
3. Start the Express server:
   ```bash
   node server.js
   ```
   *You should see a message saying `Backend server running on http://localhost:5000`.*

### 2. Start the Frontend Development Server

The frontend uses Vite and runs on **port 5173**.

1. Open a **new, separate terminal window** and navigate to the `frontend` folder:
   ```bash
   cd c:\Users\kusha\OneDrive\Desktop\E-commerece\frontend
   ```
2. Install the frontend dependencies:
   ```bash
   npm install
   ```
3. Start the Vite development server:
   ```bash
   npm run dev
   ```
   *You should see a message indicating the server is running, along with the local URL (usually `http://localhost:5173`).*

### 3. Explore the App

Open your browser and navigate to the URL provided by Vite (e.g., `http://localhost:5173`). 

- Register a new account.
- Log in with your new credentials.
- Browse products and add them to your cart.
- View and manage your cart.

---

## Project Structure

- `frontend/`: Contains the React.js application created with Vite. Connects to `http://localhost:5000` for all API calls.
- `backend/`: Contains the Node.js Express server. Uses an in-memory storage approach to keep setup minimal and fast. 
