# Bloghub 

## BlogHub

BlogHub is a fully functional full-stack blogging platform developed using HTML, CSS, and JavaScript for the frontend, and Firebase for the backend. It supports real-time blog creation, user authentication, and interactive features like likes, bookmarks, and comments.

 This is a real-time, full-stack project with over 50+ blogs already uploaded and live!

## Features
•	 Full-Stack Functionality: Combines frontend UI with a real-time Firebase backend.
•	Real-Time Updates: Posts update instantly using Firestore listeners.
•	User Authentication: Secure sign-up, login, and logout with Firebase Auth.
•	Post Management: Create, update, and delete blog posts.
•	Engage with Blogs: Like, bookmark, and comment on posts.
•        Responsive Design: Optimized for all screen sizes and devices.
•	Production-Ready: Already live with 50+ blog posts—ideal for real-world use or showcasing.

## Tech Stack
•	Frontend: HTML5, CSS
•	Backend: Firebase (Authentication + Firestore Database)
•	Firebase SDK (v9.22.0 compat):
•	firebase-app-compat.js
•	firebase-auth-compat.js
•	firebase-firestore-compat.js

## Getting Started
	1.	Clone the Repository:

    git clone https://github.com/zainab-15/BlogHub.git
    cd BlogHub


	2.	Set Up Firebase:
	•	Go to Firebase Console
	•	Create a new project.
	•	Enable Email/Password Authentication and Cloud Firestore.
	•	Copy your Firebase configuration into firebase-config.js:

    const firebaseConfig = {
    apiKey: "YOUR_API_KEY",
    authDomain: "YOUR_AUTH_DOMAIN",
    projectId: "YOUR_PROJECT_ID",
    storageBucket: "YOUR_STORAGE_BUCKET",
    messagingSenderId: "YOUR_MESSAGING_SENDER_ID",
    appId: "YOUR_APP_ID"
    };


3.	Run the App:

## Folder Structure

    BlogHub/
    ├── index.html
    ├── css/
    │   └── styles.css
    ├── js/
    │   ├── firebase-config.js
    │   ├── auth.js
    │   ├── posts.js
    │   └── main.js
    └── assets/
    └── images/


