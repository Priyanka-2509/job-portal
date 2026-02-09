# Job Portal

A full-stack job portal application built with **React (frontend)**, **Node.js + Express (backend)**, and **MongoDB (or PostgreSQL)**.  
The platform connects **candidates** and **employers** by providing job listings, applications with resume upload, dashboards, and search functionality.

Check out the live website here: [Job Portal Live](https://job-portal-1-nn19.onrender.com/)

---

##  Features

-  **User Authentication** – Login/Signup for candidates & employers  
-  **Job Listings** – Browse and search for jobs  
-  **Job Applications** – Apply to jobs with resume upload  
-  **Employer Dashboard** – Post jobs & view applicants  
-  **Candidate Dashboard** – Manage applications  
-  **Email Notifications** for job applications  
-  **Responsive UI** for mobile and desktop  

---

##  Screenshots

### Home Page
![Home Page](screenshots/home.png)

### Job Listings
![Job Listings](screenshots/jobs.png)

### Employer Dashboard
![Employer Dashboard](screenshots/employer-dashboard.png)

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- React Router  
- TailwindCSS / CSS (for styling)  

### Backend
- Node.js + Express.js  
- MongoDB Atlas / PostgreSQL (database)  
- JWT Authentication  

### Deployment
- Frontend: Netlify / Vercel  
- Backend: Render  

---

## ⚙️ Getting Started

### Prerequisites
- Node.js & npm installed  
- MongoDB Atlas or PostgreSQL database setup  

### Installation

Clone the repo:

```bash
git clone https://github.com/Priyanka-2509/job-portal.git
cd job-portal
````

Install dependencies for both frontend and backend:

```bash
# Install frontend deps
cd client
npm install

# Install backend deps
cd ../server
npm install
```

### Environment Variables

Create a `.env` file in the `server` folder with:

```
PORT=5000
MONGO_URI=your_mongo_or_postgres_connection_string
JWT_SECRET=your_secret_key
```

### ▶️ Running the App

Start backend server:

```bash
cd server
npm run dev
```

Start frontend React app:

```bash
cd client
npm start
```

The app will be available at [http://localhost:3000](http://localhost:3000) or visit the live deployment: [Job Portal Live](https://job-portal-1-nn19.onrender.com/)

---


##  Roadmap

* Setup frontend with React
* Setup backend with Express & MongoDB/PostgreSQL
* Resume upload functionality
* Advanced search & filters
* Deploy full app

---

## 🤝 Contributing

Contributions are welcome! Fork the repo and create a PR.

---

## 📜 License

This project is licensed under the MIT License.

