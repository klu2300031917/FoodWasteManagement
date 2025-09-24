# FoodWasteManagement
Batch No. 14, Project No. 39, Section No. 101, ID Nos. 2300031917, 2300031782, 2300090054


# 🍱 Food Waste Management App

A full-stack web application that allows users to **donate excess food**, **view donation success stories**, and helps reduce food waste by connecting donors to communities in need.

---

## 🚀 Features

- 👥 User authentication (register & login with reCAPTCHA)
- 🍛 Donate food with image upload
- 🗂️ View all donations (with images)
- ✅ Success stories page
- 🏠 Beautiful home screen with hero section, highlights & responsive navbar

---

## 🔧 Tech Stack

| Layer      | Technology                |
|------------|---------------------------|
| Frontend   | React.js, Axios, CSS      |
| Backend    | Node.js, Express.js       |
| Database   | MongoDB with Mongoose     |
| Tools      | Multer (file uploads), dotenv, Google reCAPTCHA |

---

## 🛠️ Installation Guide

### ✅ Prerequisites

- Node.js installed
- MongoDB running (local or cloud)
- npm (Node package manager)

---

## 🔙 Backend Setup

### 1. Navigate to backend

```bash
cd backend
```

### 2. Install dependencies

```bash
npm install express mongoose cors multer dotenv
```

### 3. Create `.env` file

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
```

### 4. Start server

```bash
node index.js
```

Or with nodemon (auto-restarts on changes):

```bash
npm install -g nodemon
nodemon index.js
```

---

## 🔜 Frontend Setup

### 1. Navigate to frontend

```bash
cd frontend
```

### 2. Install dependencies

```bash
npm install axios react-router-dom react-google-recaptcha
```

### 3. Start React app

```bash
npm start
```

The app will run on `http://localhost:3000`.

---

## 🖼️ Image Uploads

Uploaded food donation images are stored in `backend/uploads`.  
They are accessible via `http://localhost:5000/uploads/<image-filename>`.

---

## ✅ Login & Register Notes

- Google reCAPTCHA is used to prevent bots.
- Ensure the reCAPTCHA site key is correct in frontend.
- Check `.env` settings in backend for port and MongoDB.

---

## 🧪 Sample Test Accounts

```
Email: testuser@gmail.com
Password: 123456
```

---

## ⚙️ Useful Scripts

| Action               | Command                |
|----------------------|------------------------|
| Start backend        | `node index.js`        |
| Start backend (dev)  | `nodemon index.js`     |
| Start frontend       | `npm start`            |
| Install backend deps | `npm install`          |
| Install frontend deps| `npm install`          |

---

## 📸 Screenshots

> (You can add screenshots here later showing the home screen, donate form, and all donations list.)

---

## 📬 Contact

For questions or feedback, feel free to contact the developer. 


 All Rights Reserved to the Foodwastemanagement team :-
 Team lead: 1:Govindu vishnu Karthik(Project Speaker)
            2:Shaik Anas Basha(Main Programmer Frontend+Backend)
            3:N.V.D Karthik(Resourse and Error Handler)
