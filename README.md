# Khatabook Project

## Overview
This project is a web application designed to help users manage their financial transactions and keep track of their accounts. It provides features for recording transactions, viewing account history, and managing user sessions securely.

## Tech Stack
- **Backend**: Node.js with Express.js
- **Database**: MongoDB
- **Template Engine**: EJS
- **Authentication**: JWT (JSON Web Tokens)
- **File Upload**: Multer
- **Session Management**: Express-session
- **Environment Variables**: dotenv

## Project Structure
- **app.js**: Entry point of the application, sets up the Express server and middleware.
- **routes/**: Contains route definitions for different parts of the application.
- **controllers/**: Contains the logic for handling requests and responses.
- **models/**: Defines the data models for MongoDB.
- **views/**: Contains EJS templates for rendering the frontend.
- **public/**: Static files like CSS, JavaScript, and images.
- **config/**: Configuration files for database connections and other settings.
- **middlewares/**: Custom middleware for request processing.

## Setup Instructions
1. **Install Dependencies**
   ```bash
   npm install
   ```

2. **Environment Variables**
   Ensure you have a `.env` file in the root directory

3. **Database Setup**
   Make sure MongoDB is installed and running on your machine. The application connects to a local MongoDB instance.

4. **Running the Application**
   ```bash
   npm start
   ```
   The server will start on port 3000 (or the port specified in your environment variables).

## Features
- User authentication and session management
- Transaction recording and management
- Account history viewing
- Secure file uploads

## Contributing
Feel free to contribute to this project by submitting issues or pull requests.
