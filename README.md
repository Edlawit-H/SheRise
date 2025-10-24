# 🌸 SheRise — Virtual Incubator for Women Entrepreneurs (MVP)

**Team Name:** NovaHer
**Prepared For:** HerCommerce Women Hackathon

---

## 📘 Table of Contents

1. [Project Overview](#project-overview)
2. [Core Features](#core-features)
3. [User Roles](#user-roles)
4. [Tech Stack](#tech-stack)
5. [System Requirements](#system-requirements)
6. [Installation & Setup](#installation--setup)
7. [Roadmap / Future Enhancements](#roadmap--future-enhancements)
8. [Contact](#contact)

---

## 💡 Project Overview

**SheRise** is a **web-based virtual incubator** designed to empower **Ethiopian women entrepreneurs** to start, grow, and sustain their businesses.

The **MVP** focuses on:

* **Guided Learning:** Structured lesson cards and progress tracking.
* **Community Support:** A safe discussion space via **SheCircle** mini-forum.
* **Mentorship Requests:** Mentees can reach out to mentors for guidance.
* **Admin Dashboard:** Platform moderation and user management.

SheRise provides a **simple, inclusive, and culturally aligned** experience accessible to women with diverse digital literacy levels.

---

## 🚀 Core Features

### 1. 🔐 User Authentication & Profile

* Secure signup/login using **Firebase Authentication**.
* Role selection during signup (**Mentee**; mentors are external for MVP).
* Edit profile (photo, name, bio, skills, location, experience level).

### 2. 📊 Guided Growth Dashboard

* Interactive lesson cards (Beginner → Advanced).
* Track progress and mark lessons as completed.
* View personalized growth analytics (mocked for MVP).

### 3. 💬 SheCircle Community (Mini Forum)

* Create and comment on posts.
* Like posts and interact with others.
* Admins can **flag or remove inappropriate content**.

### 4. 🤝 Mentorship Request Flow

* Mentees submit mentorship requests with messages and preferences.
* Requests stored in the database for follow-up.

### 5. 🛠️ Admin & Moderation

* Admin panel to manage users, posts, and mentorship requests.
* View activity summaries and perform moderation actions.

### 6. 📈 Logging & Basic Analytics

* Tracks simple engagement metrics: user signups, mentorship requests, and posts created.

---

## 👥 User Roles

Mentee:Description--Women entrepreneurs using the platform to learn, grow, and connect.
      :Access Level--Full access to lessons, community, mentorship requests.
Mentor (External):Description--Experienced professionals offering guidance. Represented via static profiles or external links.
      :Access Level--Limited (no login for MVP).
Admin:Description--NovaHer team members managing content, users, and platform data.
     :Access Level--Full moderation and analytics access.

---

## 🧩 Tech Stack
--Frontend: React with Tailwind CSS, deployed on Vercel for fast and reliable hosting.
--Backend:Go (Golang) with Gin framework, hosted on Render (or similar) to provide scalable API services.
--Database: MongoDB Atlas for secure and flexible data storage.
--Authentication & Community Services: Firebase Authentication for secure user login and Firebase Realtime Database / Firestore to support the SheCircle community feed.
--Notifications: Firebase Cloud Messaging (FCM) to deliver real-time alerts and updates.
--Browsers & Devices: Compatible with modern desktop and mobile browsers, including Chrome, Firefox, and Edge.


---

## ⚙️ System Requirements

* **Browser:** Chrome, Firefox, Edge (latest versions)
* **Device:** Any modern desktop or mobile device
* **Internet:** Required for authentication and database access
* **Hosting:** Vercel (Frontend), Render (Backend), MongoDB Atlas (Database)

---

## 🧭 Installation & Setup

> For hackathon demo or future contributors

1. **Clone the repository:**

   ```bash
   git clone https://github.com/NovaHer/SheRise.git
   cd SheRise
   ```

2. **Frontend setup:**

   ```bash
   cd client
   npm install
   npm start
   ```

3. **Backend setup:**

   ```bash
   cd server
   go run main.go
   ```

4. **Environment variables:**
   Create `.env` files for Firebase keys, MongoDB URI, and API base URL.

---

## 🌍 Roadmap / Future Enhancements

* 💳 **Payment & Escrow:** Integration with Telebirr and Chapa.
* 🤖 **AI-Powered Mentorship:** Personalized mentor suggestions and lesson recommendations.
* 🗣️ **Real-time Chat & Video Mentorship:** WebRTC-based mentorship sessions.
* 🛍️ **E-commerce Marketplace:** Business listings for women entrepreneurs.
* 🌐 **Full Localization:** Support for Amharic, Oromiffa, and Tigrigna.
* 📱 **Mobile App Version:** Cross-platform PWA for Android/iOS.

---

## 📫 Contact

For questions, collaborations, or contributions:
**Team NovaHer**

* 💌 [GitHub Repository](https://github.com/Edlawit-H/SheRise/tree/main)
* 🌸 Hackathon Contact: [HerCommerce Hackathon 2025]

---



