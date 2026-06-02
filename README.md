# HireLink - Job Board Platform - Team 2

A full-stack Job Board Platform built for CSC 202. This platform connects employers with job seekers.

---

##  Links
- Live App: [HireLink](hire-link-eta.vercel.app)

---

##  Tech Stack
- Frontend: React.js
- Backend: Node.js, Express.js, TypeScript
- Database: MongoDB

---

##  Team Members

| Name | Role |
|------|------|
| Fawaz Salimanu | Team Lead |
| Jason | Backend |
| David Alamutu | Backend |
| Hillary Ilona | Frontend |
| Muhammad Nasiru | Frontend |
| Anthony Okpuruka | DevOps |
| Tomba Bobmanuel | QA / Documentation |
| Timilehin Adeyoyin | QA / Documentation |

---

## Setup Instructions
To be added.

---

##  API Documentation
To be added.

---

##  Testing
To be added.

##  API Documentation

### Job Routes

GET /api/jobs  
Fetch all jobs

GET /api/jobs/:id  
Fetch single job

POST /api/jobs  
Create job

PUT /api/jobs/:id  
Update job

DELETE /api/jobs/:id  
Delete job

---

### Auth Routes

POST /api/users/register  
Register user

POST /api/users/login  
Login user

---

### Application Routes

POST /api/applications  
Apply to job

##  Pages

### Home Page
- Search bar
- Recently added jobs

### Job Listings
- Filter by category
- Filter by location

### Job Details
- Full job description
- Apply button

### Employer Dashboard
- View posted jobs
- View applications

### Post Job
- Create job form

### Login/Register
- User authentication
BUG:
POST /api/jobs crashes if location field is missing.

Expected:
Validation error message.

Actual:
Server crashes.
##  Screenshots

(Add screenshots here)
##  Live Demo

Frontend: https://...
Backend: https://...



# HireLink
HireLink is a full-stack job board platform designed to connect employers with job seekers efficiently. Employers can post job openings, while job seekers can browse listings and apply for positions.
This project was developed as part of the CSC 202 - Computer Programming II group project.

## Features

- User Authentication
- Job Listings
- Job Applications
- Employer Dashboard
- Search and Filtering
- Responsive User Interface
- REST API Integration

## Tech Stack

### Frontend
- React.js
- Material UI

### Backend
- Node.js
- Express.js
- MongoDB

