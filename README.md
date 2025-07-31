# Study Notion

## Overview
This project is a full-stack web application that includes a backend server built with Node.js, Express, and Mongoose, and a frontend client developed with React.js and Tailwind CSS. The application also integrates various tools such as Cloudinary for image uploading, a mail sender for sending emails, and Express File Uploader for handling file uploads.

## Features
✅ User authentication and authorization  
🖼️ Image uploading with Cloudinary  
📧 Email notifications  
📁 File uploads  
🔄 RESTful API  
📱 Responsive design with Tailwind CSS  

## Technologies Used

### Backend
- Node.js
- Express
- Mongoose
- Cloudinary
- Nodemailer
- Express File Uploader

### Frontend
- React.js
- Tailwind CSS

## Prerequisites
Before you begin, ensure you have met the following requirements:
- Node.js and npm installed on your machine
- MongoDB installed and running locally or a MongoDB Atlas account

## Installation

1. Clone the repository:
```bash
git clone https://github.com/rajnishkumar13500/StudyNotion-.git
cd StudyNotion
```

2. Set up the backend:
```bash
cd server
npm install
```

3. Set up the frontend:
```bash
cd frontend
npm install
```

## Configuration

### Backend
Create a `.env` file in the server directory and add the following environment variables:

```env
PORT=5000
MONGODB_URI=your-mongodb-uri
CLOUDINARY_CLOUD_NAME=your-cloudinary-cloud-name
CLOUDINARY_API_KEY=your-cloudinary-api-key
CLOUDINARY_API_SECRET=your-cloudinary-api-secret
EMAIL_USER=your-email@example.com
EMAIL_PASS=your-email-password
```

### Frontend
Create a `.env` file in the client directory and add the following environment variables:
```env
REACT_APP_API_URL=http://localhost:5000
```

## Running the Application

Start the backend server:
```bash
cd server
npm start
```

Start the frontend development server:
```bash
cd frontend
npm start
```

Open your browser and navigate to http://localhost:3000.
