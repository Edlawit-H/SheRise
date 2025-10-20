# SheRise - Virtual Incubator for Women Entrepreneurs (MVP)

**Team Name:** NovaHer  
**Prepared For:** HerCommerce Women Hackathon  

---

## Table of Contents
1. [Project Overview](#project-overview)  
2. [Features](#features)  
3. [User Roles](#user-roles)  
4. [Tech Stack](#tech-stack)  
5. [System Requirements](#system-requirements)  
6. [Installation](#installation)  
7. [Future Enhancements](#future-enhancements)  

---

## Project Overview
**SheRise** is a web-based virtual incubator designed to empower Ethiopian women entrepreneurs to start and grow their businesses from home. The MVP focuses on:

- Guided learning through lesson cards and actionable tasks.
- Community support via SheCircle mini-forum.
- Mentorship request flow for connecting mentees with external mentors.

The platform is aimed at providing a simple, intuitive, and inclusive experience for women with varying levels of digital literacy.

---

## Features

### 1. User Authentication & Profile
- Sign up and login securely using Firebase Authentication.
- Role selection at signup (Mentee; mentors are external for MVP).
- Edit user profile: name, photo, bio, skills, location, and level.

### 2. Guided Growth Dashboard
- Displays 3–6 lesson cards per user level (Beginner, Intermediate, Advanced).
- Mark lessons as complete and track progress percentage.

### 3. SheCircle Community (Mini Forum)
- Create posts and comments.
- Like posts and comment threads.
- Admin moderation for inappropriate content.

### 4. Mentorship Request Flow
- Mentees submit mentorship requests to external mentors.
- Requests are stored in the database for future follow-up.

### 5. Admin & Moderation
- Admin panel for user management, posts, and mentorship requests.
- Admins can flag or delete content and deactivate users.

### 6. Logging & Basic Analytics
- Track basic metrics: signups, posts, mentorship requests.

---

## User Roles

- **Mentees:** Women entrepreneurs using the platform to learn, connect, and grow.  
- **Mentors (External for MVP):** Experienced professionals providing guidance. Represented via profiles or external links.  
- **Admins:** NovaHer team members managing users, content, and mentorship requests.

---

## Tech Stack

- **Frontend:** React.js + Tailwind CSS (Deployed on Vercel)  
- **Backend:** Go (Golang) + Gin framework (Deployed on Render or similar)  
- **Database:** MongoDB Atlas  
- **Authentication & Community:** Firebase Authentication & Firestore / Realtime Database  
- **Notifications:** Firebase Cloud Messaging (FCM)  

---

## System Requirements

- Modern web browser: Chrome, Firefox, Edge  
- Internet connection  
- No special hardware required  

---

## Roadmap / Future Enhancements
- Payments and Escrow integration with Telebirr and Chapa  
- Real-time chat and video mentorship  
- AI-powered mentorship with personalized lesson recommendations  
- Business showcase marketplace for women-led businesses  
- Full localization (Amharic, Oromiffa, Tigrigna)  

## Contact
For questions or collaboration, reach out to the NovaHer team via GitHub or hackathon contacts.
