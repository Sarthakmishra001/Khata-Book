# 📘 Khatabook Project

> A simple, secure, and efficient account and transaction manager – inspired by the traditional Indian "Bahi-Khata" system.

---

## 📌 Overview

**Khatabook** is a web application that helps users manage their **financial transactions**, view **account histories**, and securely handle user sessions. It's designed with simplicity and practicality in mind for small businesses or personal use.

---

## 🚀 Tech Stack

- **Backend**: Node.js with Express.js  
- **Database**: MongoDB  
- **Templating Engine**: EJS  
- **Authentication**: JWT (JSON Web Tokens)  
- **File Upload**: Multer  
- **Session Management**: express-session  
- **Environment Variables**: dotenv  

---

## 📁 Project Structure

Khatabook/ │ ├── app.js # Entry point ├── routes/ # Application routes ├── controllers/ # Route logic ├── models/ # MongoDB schemas ├── views/ # EJS templates ├── public/ # Static assets (CSS, JS, Images) ├── config/ # Configuration files ├── middlewares/ # Custom middlewares └── .env # Environment variables

## ⚙️ Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/khatabook.git
   cd khatabook
2. **Install dependencies**

    npm install
3.**Configure environment variables**

  Create a .env file in the root with:
  PORT=3000
  MONGODB_URI=mongodb://localhost:27017/khatabook
  JWT_SECRET=your_jwt_secret
4.**Run the application**  
    npm start
    Open http://localhost:3000 in your browser.
    
**✨ Features**
1> Secure login system with JWT

2> Add, update, and delete financial transactions

3> View transaction and account history

4> Upload and manage receipts/files

5> Session handling and flash messaging
