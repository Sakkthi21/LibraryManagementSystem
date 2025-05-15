# Library Management System

A Node-based library management system with Firebase integration for managing books and members.

## 📚 Features

### Core Functionality
- User Authentication
- Dashboard Overview
- Book Management
- Member Management
- Real-time Updates

### Components
- Login - Secure authentication interface
- Dashboard - Overview of library statistics
- Books - Manage book inventory
- Members - Handle member records
- Sidebar - Navigation component

## 🛠 Tech Stack

- React.js
- Firebase
  - Authentication
  - Firestore Database
- Context API for state management
- CSS for styling

## 🏗 Project Structure

```
src/
  ├── components/     # React components
  │   ├── Books.jsx
  │   ├── Dashboard.jsx
  │   ├── Login.jsx
  │   ├── Members.jsx
  │   └── Sidebar.jsx
  ├── context/        # Context providers
  │   └── AuthContext.js
  ├── firebase.js     # Firebase configuration
  ├── App.js          # Main application component
  ├── index.js        # Application entry point
  └── index.css       # Global styles
```

## 🚀 Getting Started

1. Install dependencies
```bash
npm install
```

2. Set up Firebase configuration
- Create a Firebase project
- Enable Authentication and Firestore
- Copy your Firebase config to `src/firebase.js`

3. Start the development server
```bash
npm start
```

## 🔐 Authentication

The application uses Firebase Authentication for secure user management:
- Email/Password authentication
- Protected routes for authenticated users
- User session management

## 📱 Features Overview

### Dashboard
- Overview of total books and members
- Recent activity tracking
- Quick access to main functions

### Book Management
- Add new books
- Update book details
- Remove books from inventory
- View book availability

### Member Management
- Register new members
- Update member information
- Track borrowed books
- Manage member status

