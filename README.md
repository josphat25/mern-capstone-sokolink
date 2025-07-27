# MERN Stack Capstone Project

This assignment focuses on designing, developing, and deploying a comprehensive full-stack MERN application that showcases all the skills you've learned throughout the course.

## Assignment Overview

You will:
1. Plan and design a full-stack MERN application
2. Develop a robust backend with MongoDB, Express.js, and Node.js
3. Create an interactive frontend with React.js
4. Implement testing across the entire application
5. Deploy the application to production

## Getting Started

1. Accept the GitHub Classroom assignment
2. Clone the repository to your local machine
3. Follow the instructions in the `Week8-Assignment.md` file
4. Plan, develop, and deploy your capstone project

## Files Included

- `Week8-Assignment.md`: Detailed assignment instructions

## Requirements

- Node.js (v18 or higher)
- MongoDB (local installation or Atlas account)
- npm or yarn
- Git and GitHub account
- Accounts on deployment platforms (Render/Vercel/Netlify/etc.)

## Project Ideas

The `Week8-Assignment.md` file includes several project ideas, but you're encouraged to develop your own idea that demonstrates your skills and interests.

## Submission

Your project will be automatically submitted when you push to your GitHub Classroom repository. Make sure to:

1. Commit and push your code regularly
2. Include comprehensive documentation
3. Deploy your application and add the live URL to your README.md
4. Create a video demonstration and include the link in your README.md

## Project Name: SokoLink – Smart Market Access for Small-Scale Farmers
# Problem Statement:
1.Small-scale farmers often struggle with:

2.Lack of access to current market prices

3.Middlemen exploitation

4.Limited visibility to direct buyers or cooperatives

5.Poor record-keeping and loss of income tracking

##  Solution (Your App):
A MERN stack platform that connects small-scale farmers to the marketplace directly.

## Core Features:
1.Live Market Prices: Real-time pricing data for common crops in local and nearby markets.

2. Produce Listings: Farmers can list their crops with quantity, price, and location.

3. Buyer-Farmer Connection: Buyers can filter by crop, location, and contact farmers directly.

4. Sales Dashboard: Visualize income, volume sold, best-performing crops.

5. Alerts System: Notify farmers of price spikes, weather events, or nearby bulk buyer interest.

6. Multilingual Support: Kiswahili & English support for inclusivity.

## SokoLink Project Mind Map

sokoLink - Smart Market Access Platform
|
├── 1. User Management
|    ├── Farmer Signup/Login
|    ├── Buyer Signup/Login
|    ├── Profile Management
|
├── 2. Produce Listings
|    ├── Create/Edit/Delete Listings
|    ├── Add Price, Quantity, Location, Images
|    ├── Search & Filter by Crop, Region
|
├── 3. Live Market Prices
|    ├── API Integration or Manual Data Input
|    ├── Region-based Price Comparison
|    ├── Historical Price Graphs
|
├── 4. Buyer-Farmer Interaction
|    ├── Direct Messaging or Contact Info
|    ├── Bulk Request Feature
|    ├── Buyer Reviews
|
├── 5. Sales Tracking Dashboard
|    ├── Monthly Earnings
|    ├── Crop Performance
|    ├── Visual Reports (Charts/Graphs)
|
├── 6. Alerts System
|    ├── Price Spike Notifications
|    ├── Weather Updates
|    ├── New Buyer Listings Nearby
|
├── 7. Multilingual Support
|    ├── Kiswahili ↔ English Toggle
|
├── 8. Admin Panel
|    ├── Approve Listings
|    ├── Monitor Platform Activity
|    ├── Manage Users
|
└── 9. Deployment & CI/CD
     ├── Backend: Render or Railway
     ├── Frontend: Vercel or Netlify
     ├── GitHub Actions CI/CD
     ├── MongoDB Atlas for DB
     ├── Monitoring: Sentry, Health Checks

##  SMART Goals for SokoLink Capstone
Goal	Description
S - Specific	Build a MERN-based web application that connects small-scale farmers with local buyers and gives them access to live market prices and sales tracking tools.
M - Measurable	Complete development of 6 core features (auth, listings, prices, messaging, dashboard, alerts) and deploy both frontend and backend by the end of Week 8.
A - Achievable	Use existing tools (MongoDB Atlas, Vercel, Render, GitHub Actions) and learned skills (React, Express, Node.js, MongoDB, CI/CD) to complete all tasks.
R - Relevant	Addresses a major pain point in agriculture—lack of market access—and empowers farmers through technology.
T - Time-bound	Final deployed product (with CI/CD and documentation) ready in 4 weeks, with weekly milestones for progress tracking.

## Tech Stack & Tools
Component	          Tech/Tool
Frontend	          React.js (Create React App / Vite)
Backend	          Node.js v18+, Express.js
Database	          MongoDB (Atlas or local)
Package Manager	npm (or yarn)
Version Control	Git & GitHub
CI/CD	          GitHub Actions
Frontend Hosting	Vercel (or Netlify)
Backend Hosting	Render (or Railway/Heroku)
Monitoring	     Sentry, UptimeRobot, Healthcheck

## Project Features
1. Authentication
Farmers and Buyers can sign up/log in

JWT-based authentication

Role-based access (farmer, buyer, admin)

2. Produce Listings
Farmers add, update, and delete produce

Buyers can search/filter listings

Images uploaded via Cloudinary or local folder

3. Live Market Prices
Prices per crop by region

Admin can update prices manually or via external API

4. Buyer-Farmer Connection
Buyers can send purchase interest

Optional real-time chat (Socket.io or message requests)

5. Sales Dashboard
Track number of sales per crop

Income statistics

Graphs using Chart.js or Recharts

6. Alerts
Email alerts for price changes or buyer requests

SMS/Push notifications (optional using Twilio or OneSignal)

## Folder Structure
/backend
├── controllers/
├── models/
├── routes/
├── config/
├── middleware/
├── server.js
├── .env

/frontend
├── src/
│   ├── components/
│   ├── pages/
│   ├── context/
│   ├── api/
│   └── App.js
├── .env

## Deployment Plan
Step	                  Tool/Platform
Backend Deployment	   Render (with GitHub integration)
Frontend Deployment	   Vercel (linked to GitHub repo)
CI/CD	             GitHub Actions (run tests, build, deploy)
Environment Variables  Render, Vercel (.env vars for API, DB)
MongoDB Hosting	   MongoDB Atlas (Free Tier)
Monitoring Tools	   Sentry, UptimeRobot

## Environment Variables
Add .env.example in both frontend and backend:
# Backend
PORT=5000
MONGO_URI=mongodb+srv://<username>:<password>@cluster.mongodb.net/farmlink
JWT_SECRET=your_jwt_secret
CLOUDINARY_URL=...
# Frontend
REACT_APP_API_BASE_URL=https://your-backend-url.com/api

# 🌾 FarmLink

&#x20;&#x20;

FarmLink is a MERN (MongoDB, Express, React, Node.js) stack application designed to empower small-scale farmers by connecting them with local markets, buyers, and real-time agricultural insights. Built with a clean UI, live market data, and modern authentication, FarmLink ensures farmers can list, sell, and track produce efficiently.

## 🚀 Live Demo

* 🌐 Frontend: [https://farmlink-frontend.vercel.app](https://farmlink-frontend.vercel.app)
* 🔗 Backend API: [https://farm-backend-8xkh.onrender.com/api](https://farm-backend-8xkh.onrender.com/api)

---

## 📌 Features

* ✅ Farmer and Buyer Registration/Login (JWT Authentication)
* 📦 Post and View Agricultural Produce (Fruits, Vegetables, Grains)
* 📈 Live Market Prices
* 🛒 Connect with Potential Buyers
* 📲 Responsive UI (Mobile/Desktop)
* 🔒 Protected Routes and Role-Based Access
* 🧾 Sales History and Tracking
* ⚠️ Real-time Alerts and Updates
* 🌐 RESTful API Integration

---

## 🖼️ Screenshots *(to add)*

| Homepage | Produce Listings | Dashboard |
| -------- | ---------------- | --------- |
|          |                  |           |

---

## 🧠 Tech Stack

### Frontend:

* React 18
* React Router DOM
* Tailwind CSS
* Axios
* Vite

### Backend:

* Node.js + Express
* MongoDB + Mongoose
* JWT Authentication
* CORS, dotenv, bcrypt, express-validator

---

## 🛠️ Installation

1. **Clone the repository**

```bash
git clone https://github.com/josphat25/mern-capstone-sokolink.git
cd mern-capstone-sokolink
```

2. **Frontend Setup**

```bash
cd frontend
npm install
npm run dev
```

3. **Backend Setup**

```bash
cd backend
npm install
npm run dev
```

4. **Environment Variables**

Create `.env` in the frontend folder:

```
VITE_API_URL=https://farm-backend-8xkh.onrender.com/api
```

Create `.env` in the backend folder:

```
PORT=5000
MONGO_URI=your_mongo_db_uri
JWT_SECRET=your_secret_key
```

---

## 📁 Folder Structure (Frontend)

```
src/
│
├── assets/               # Images and media
├── components/           # Reusable components
├── context/              # Auth / Global state
├── pages/                # Route pages (Home, Produce, Login)
│   ├── produce/
│   │   ├── fruits.jsx
│   │   ├── grains.jsx
│   │   └── vegetables.jsx
│   └── produce.jsx
├── App.jsx
└── main.jsx
```

---

## 🚀 Deployment

* **Frontend**: Vercel
* **Backend**: Render

---

## 🤝 Contributing

Contributions are welcome! Please fork the repository and open a pull request with clear commits.

---

## 📄 License

This project is licensed under the MIT License.

---

## 🙋‍♂️ Author

**Josphat Ndungu**
📧 [josphatmukuha24@gmail.com](mailto:josphatmukuha24@gmail.com)

---

## 📌 Acknowledgements

* Dev Academy MERN Capstone Program
* Farmers and Agritech advocates in Kenya




 
## Resources

- [MongoDB Documentation](https://docs.mongodb.com/)
- [Express.js Documentation](https://expressjs.com/)
- [React Documentation](https://react.dev/)
- [Node.js Documentation](https://nodejs.org/en/docs/)
- [GitHub Classroom Guide](https://docs.github.com/en/education/manage-coursework-with-github-classroom) 
