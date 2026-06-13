# SmartLink 🔗

A modern full-stack URL shortener platform that helps users create, manage, and analyze short links with ease.

SmartLink transforms long URLs into clean, shareable links while providing powerful insights through analytics, QR code generation, custom aliases, link expiry, and bulk URL shortening.

---

## ✨ Features

### 🔐 Authentication

* User registration and login
* JWT-based authentication
* Secure password hashing using bcrypt

### 🔗 URL Shortening

* Convert long URLs into short, shareable links
* Generate unique short codes automatically
* Support for custom aliases

### 📱 QR Code Generation

* Generate QR codes for every shortened link
* Easy sharing across devices and platforms

### ⏰ Link Expiry

* Set expiry dates for links
* Prevent access after expiration

### 📊 Analytics Dashboard

* Track total clicks
* View browser statistics
* Analyze device usage
* Monitor operating systems
* Visualize daily traffic trends

### 📂 Link Management

* Dashboard to manage all created links
* Search and organize links efficiently
* View public statistics for shortened URLs

### 📥 Bulk URL Shortening

* Upload multiple URLs using CSV files
* Generate short links in a single operation

---

## 🛠 Tech Stack

### Frontend

* React
* Vite
* Tailwind CSS

### Backend

* Node.js
* Express.js

### Database

* MongoDB Atlas

### Authentication

* JWT (JSON Web Tokens)
* bcrypt

### Testing

* Jest
* Supertest

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

* Node.js (v18 or above)
* npm
* MongoDB Atlas account
* Git

---

## 📁 Project Structure

```
SmartLink/
├── frontend/
│   ├── src/
│   └── package.json
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── tests/
│   └── package.json
│
└── README.md
```

---

## ⚙️ Environment Variables

### Backend (.env)

```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
BASE_URL=http://localhost:5000
```

### Frontend (.env)

```env
VITE_API_URL=http://localhost:5000
```

---

## 💻 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/smartlink.git
cd smartlink
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

Backend runs on:

```
http://localhost:5000
```

### Frontend Setup

Open a new terminal:

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 🔄 How It Works

1. Users sign up or log in.
2. Enter a long URL.
3. Optionally add:

   * Title
   * Custom alias
   * Expiry date
4. SmartLink generates a shortened URL.
5. The shortened link is stored in MongoDB Atlas.
6. When the link is accessed:

   * The user is redirected.
   * Analytics data is recorded.
7. Users can monitor performance through the dashboard.

---

## 🧪 Running Tests

Backend tests can be executed using:

```bash
cd backend
npm test
```

---

## 📊 Analytics Captured

SmartLink records useful metrics such as:

* Total clicks
* Browser information
* Device type
* Operating system
* Daily click trends
* Public statistics for shared links

---

## 🌟 Why SmartLink?

SmartLink is more than just a URL shortener.

It provides valuable insights that help users understand how their links perform while offering convenient sharing options through QR codes and bulk operations.

This project demonstrates real-world full-stack development concepts including authentication, database integration, analytics, testing, and modern frontend development.

---

## 🔮 Future Enhancements

* Team collaboration features
* Custom domains
* Geo-location analytics
* Password-protected links
* Email notifications
* Advanced filtering and exports

---

