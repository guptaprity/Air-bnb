# 🏡 Airbnb Clone  

![License](https://img.shields.io/badge/license-MIT-blue.svg)  
![Stars](https://img.shields.io/github/stars/guptaprity/airbnb-clone.svg)  
![Forks](https://img.shields.io/github/forks/guptaprity/airbnb-clone.svg)  

A **full-stack Airbnb Clone** built with **React**, **Node.js**, **Express**, and **MongoDB**, featuring property listings, authentication, bookings, and a responsive UI.  

---

## 📑 Table of Contents
- [✨ Features](#-features)
- [🛠 Tech Stack](#-tech-stack)
- [📂 Project Structure](#-project-structure)
- [⚙ Installation & Setup](#-installation--setup)
- [🔐 Environment Variables](#-environment-variables)
- [▶ Usage](#-usage)
- [🔗 Live Demo](#-live-demo)
- [🚀 Future Improvements](#-future-improvements)
- [🤝 Contributing](#-contributing)
- [📜 License](#-license)

---

## ✨ Features
✔ User Authentication (Signup/Login)  
✔ Add, Edit, Delete Listings  
✔ Search & Filter Properties by Location and Price  
✔ Booking & Reservation System  
✔ Image Upload for Properties  
✔ Responsive Design for All Devices  

---

## 🛠 Tech Stack
**Frontend:** React.js, Tailwind CSS  
**Backend:** Node.js, Express.js  
**Database:** MongoDB  
**Authentication:** JWT  
**Deployment:** Vercel / Netlify (Frontend), Render / Heroku (Backend)  

---

## 📂 Project Structure
airbnb-clone/
│

airbnb-clone/
│
├── client/ # React Frontend

│ ├── public/

│ ├── src/

│ │ ├── components/ # Reusable UI components

│ │ ├── pages/ # Pages for the application

│ │ ├── styles/ # CSS / Tailwind styles

│ │ └── utils/ # Utility functions

│ └── package.json
│

├── server/ # Node.js Backend

│ ├── controllers/ # Request handlers

│ ├── models/ # Database models

│ ├── routes/ # API routes

│ ├── server.js # Main backend file

│ └── package.json
│
├── .gitignore

└── README.md


---


## ⚙ Installation & Setup

## **1. Clone the Repository**
```bash
git clone https://github.com/your-username/airbnb-clone.git
cd airbnb-clone
````
2. Install Dependencies

For frontend:
```
cd client
npm install
```

🔐 Environment Variables

Create a .env file inside server/ and add:
```
MONGO_URI=your_mongo_database_url
JWT_SECRET=your_secret_key
PORT=5000
```

▶ Usage
```
Start backend:
cd server
npm run dev
```

Start frontend:
```
cd client
npm start
```
🔗 Live Demo

👉 https://airbnb-clone-tts5.onrender.com/listings

🚀 Future Improvements

Add Payment Gateway (Stripe)

Add Reviews & Ratings

Add Advanced Filters & Sorting

Implement Multi-language Support

### 🤝 Contributing

Contributions are welcome!

Fork the repo

Create a new branch (feature-branch)

Commit your changes

Push to the branch

Create a pull request

### 📜 License

This project is licensed under the MIT License.




