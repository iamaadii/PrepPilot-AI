# 🚀 Pre-Pilot AI

> **An AI-powered Interview Preparation Platform that helps job seekers analyze their resume, identify skill gaps.**

![React](https://img.shields.io/badge/Frontend-React-61DAFB)
![Node.js](https://img.shields.io/badge/Backend-Node.js-339933)
![Express.js](https://img.shields.io/badge/Framework-Express-black)
![MongoDB](https://img.shields.io/badge/Database-MongoDB-47A248)
![Gemini](https://img.shields.io/badge/AI-Google%20Gemini-blue)

---

# 📖 Overview

Preparing for interviews requires more than just a good resume—it requires understanding how well your profile aligns with a specific job.

**Pre-Pilot AI** is an AI-powered web application that analyzes a candidate's **Resume**, **Self Description**, and **Job Description** to generate a complete interview preparation report.

The platform provides:

* Resume vs Job Match Score
* Technical Interview Questions
* Behavioral Interview Questions
* Skill Gap Analysis
* Personalized Preparation Roadmap
* ATS-Friendly Resume Generation

Everything is tailored specifically to the target job role using **Google Gemini AI**.

---

# ✨ Features

## 📄 Resume Analysis

Upload your resume in PDF format and let AI analyze it against the provided job description.

---

## 🎯 Resume Match Score

Receive an AI-generated match score that indicates how closely your profile aligns with the job requirements.

---

## 💻 Personalized Technical Interview Questions

Generate role-specific technical interview questions with:

* Expected Answer
* Interviewer's Intention

---

## 💬 Behavioral Interview Questions

Prepare for HR and behavioral rounds through AI-generated questions along with:

* Expected Response
* Purpose behind each question

---

## 📉 Skill Gap Analysis

Identify the missing skills required for your target role.

Each skill is classified as:

* 🟢 Low Priority
* 🟡 Medium Priority
* 🔴 High Priority

---

## 📅 Personalized Preparation Plan

Generate a day-wise interview preparation roadmap based on your:

* Resume
* Current Skillset
* Target Role
* Job Description

---

## 📑 ATS-Friendly Resume Generator

Generate an optimized resume tailored specifically for the target job description.

---

## 🔐 Secure Authentication

* User Registration
* Login
* JWT Authentication
* Secure Logout using Token Blacklisting

---

## 📚 Interview Report History

All generated reports are securely stored and can be accessed anytime.

---

# 🤖 AI Integration

Pre-Pilot AI uses **Google Gemini** with the **`gemini-3-flash-preview`** model to intelligently analyze candidate profiles and generate personalized interview preparation content.

The AI performs:

* Resume Analysis
* Job Description Understanding
* Resume Match Score Calculation
* Technical Question Generation
* Behavioral Question Generation
* Skill Gap Identification
* Personalized Study Plan Generation
* ATS-Friendly Resume Generation

---

# 🛠 Tech Stack

### Frontend

* React.js
* SCSS
* JavaScript
* Axios

### Backend

* Node.js
* Express.js

### Database

* MongoDB
* Mongoose

### Authentication

* JWT
* bcrypt.js

### AI

* Google Gemini API
* Model: `gemini-3-flash-preview`

### File Upload

* Multer

---

# 🏗 System Architecture

```text
                  +----------------------+
                  |      React Frontend  |
                  +----------+-----------+
                             |
                       REST API Requests
                             |
                  +----------v-----------+
                  |   Express.js Server  |
                  +----------+-----------+
                             |
        +--------------------+--------------------+
        |                    |                    |
 Authentication        Resume Upload       AI Processing
        |                    |                    |
        +--------------------+--------------------+
                             |
                    Google Gemini API
                             |
                    MongoDB Database
```

---

# 🚀 Getting Started

## Clone the Repository

```bash
git clone https://github.com/your-username/pre-pilot-ai.git
cd pre-pilot-ai
```

---

## Install Dependencies

### Backend

```bash
cd server
npm install
```

### Frontend

```bash
cd client
npm install
```

---

## Environment Variables

Create a `.env` file inside the server directory.

```env
PORT=5000

MONGODB_URI=your_mongodb_connection_string

JWT_SECRET=your_jwt_secret

GEMINI_API_KEY=your_google_gemini_api_key
```

---

## Start the Application

### Backend

```bash
npm run dev
```

### Frontend

```bash
npm start
```

---

# 📸 Screenshots
* Register
<img width="1906" height="832" alt="Screenshot 2026-06-28 213343" src="https://github.com/user-attachments/assets/5468bacb-4111-4229-8dbc-b4d2e92d4661" />

---

* Login
<img width="1908" height="885" alt="Screenshot 2026-06-28 213029" src="https://github.com/user-attachments/assets/8727e0cc-86bc-4b69-9a40-c12552812062" />

---

* Home Page
<img width="1900" height="861" alt="Screenshot 2026-06-28 213457" src="https://github.com/user-attachments/assets/cbc8283f-e9c3-4891-ab39-a150e9e0e40a" />

---

* AI Report
<img width="1888" height="865" alt="Screenshot 2026-06-28 213610" src="https://github.com/user-attachments/assets/959f9e10-e8e5-4694-9759-f8301f2ad72d" />

---
