# HireLink 💼

**HireLink** is a full-stack Job Board Platform developedby group 2 . The platform connects employers with job seekers through a modern, responsive, and user-friendly web application.

Employers can create accounts, post job opportunities, and manage applications, while job seekers can browse available positions, search for relevant jobs, and apply directly through the platform.


## 📖 Project Overview

The goal of HireLink is to simplify the recruitment process by providing a centralized platform where employers and job seekers can interact efficiently.

### Objectives

- Provide an easy-to-use job search platform.
- Enable employers to create and manage job listings.
- Allow job seekers to apply for available opportunities.
- Demonstrate the implementation of a full-stack web application using modern technologies.

## ✨ Features

### 👤 Authentication
- User Registration
- User Login
- Secure authentication system
- Separate user roles (Employers & Job Seekers)

### 💼 Job Management
- Create new job postings
- Edit existing job postings
- Delete filled or expired jobs
- View detailed job information

### 🔍 Job Search
- Browse available jobs
- Search jobs by keyword
- Filter jobs by:
  - Category
  - Location
  - Employment Type

### 📄 Applications
- Apply for available jobs
- Employers can view submitted applications
- Application tracking

### 📱 Responsive Design
- Modern and intuitive user interface
- Optimized for desktop and mobile devices

---

## 🛠️ Tech Stack

### Frontend
- Next.js
- TypeScript
- Tailwind CSS

### Backend
- Node.js
- Express.js
- TypeScript
- React

### Database
- PostgreSQL

### Development Tools
- Git & GitHub
- VS Code
- Vercel

## 🏗️ System Architecture

```
User
   │
   ▼
Frontend (Next.js)
   │
   ▼
Backend API (Express.js)
   │
   ▼
PostgreSQL Database


## 📂 Project Structure


HireLink/
│
├── frontend/
│   ├── public/
│   ├── src/
│   ├── .next/
│   └── node_modules/
│
├── backend/
     app/
│   ├── application/
│   ├──auth/
│   ├── bookmarks/
│   ├── core/
│   ├── jobs/
│   └── notifications/
    └── users/
│
├── README.md
└── .gitignore
```

---

## 🖥️ Pages

### Home / Landing Page
- Hero section
- Search bar
- Recently added jobs

### Job Listings
- View all jobs
- Filter by category
- Filter by location
- Filter by employment type

### Job Details Page
- Full job description
- Requirements
- Company information
- Apply button

### Employer Dashboard
- View posted jobs
- Manage job listings
- View applications

### Post a Job
- Create a new job listing
- Submit vacancy details

### Login / Register
- User authentication
- Employer and Job Seeker accounts

### Admin dashboard
- check all users
- check job posting

---

## 🔌 API Endpoints

### Job Routes

| Method | Endpoint | Description |
|----------|------------------|------------------------------|
| GET | `/api/jobs` | Fetch all jobs |
| GET | `/api/jobs/:id` | Fetch a single job |
| POST | `/api/jobs` | Create a new job |
| PUT | `/api/jobs/:id` | Update an existing job |
| DELETE | `/api/jobs/:id` | Delete a job |

---

### User Routes

| Method | Endpoint | Description |
|----------|--------------------------|----------------------|
| POST | `/api/users/register` | Register a new user |
| POST | `/api/users/login` | Authenticate a user |

---

### Application Routes

| Method | Endpoint | Description |
|----------|----------------------------|-------------------------|
| POST | `/api/applications` | Submit a job application |



### Clone the Repository

```bash
git clone https://github.com/faweeezee/HireLink.git
cd HireLink
```


## 🔐 Environment Variables

DATABASE_URL=postgresql://postgres.hbvgkckkrrifnmkhdzyh:HireLink%402026%23@aws-0-eu-west-1.pooler.supabase.com:5432/postgres
JWT_SECRET=hirelink_super_secret_key_2024
PORT=5001

EMAIL_USER=davidalamutu@gmail.com
EMAIL_PASS=ytgm kcxx mjgf qjxa

CLIENT_URL=http://localhost:3000

NODE_ENV=development
```

---

## 🧪 Testing

The backend API and application functionality were tested using:

- Thunder Client

### Testing Scope

- User authentication
- Job CRUD operations
- Application submission
- Route validation
- Error handling
- Database integration

---

## 🚀 Deployment

### Frontend

Deployed using:

- Vercel

### Backend

Deployed using:

- Render


---

## 👥 Team Members

| Name | Matric Number | Role |
| :--- | :--- | :--- |
| Fawaz Salimanu | 24120112053 | Team Lead |
| Jason | Backend Developer |
| David Alamutu | 24120112009 | Backend Developer |
| Hillary Ilona | 25120112059 | Frontend Developer |
| Muhammad Nasiru | 24120112032 | Frontend Developer |
| Anthony Okpuruka | 24120112044 | DevOps / Integration |
| Tomba Bobmanuel | 24120112016 | QA / Documentation |
| Timilehin Adeyoyin | 24120112003 | QA / Documentation |

---

## 🤝 Collaboration Workflow

The project was developed collaboratively using Git and GitHub. Team members worked on separate tasks and integrated their contributions through version control and regular testing.

---

## 🔮 Future Improvements

- Resume upload functionality
- Email notifications
- Admin dashboard
- Job recommendation system
- Real-time application tracking
- Mobile application support

---

## 📚 Course Information

**Course:** CSC 202 – Computer Programming II

**Project Title:** HireLink – Full-Stack Job Board Platform

---

## 📜 License

This project was developed for educational purposes as part of the CSC 202 course requirements.

---

## 🙏 Acknowledgements

Special thanks to the course instructors  and all team members for their collaboration and contributions toward the successful completion of this project.