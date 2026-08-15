# StayEmbrace 🏠

A full-stack hostel management web application built as a Final Year Project (FYP), designed to digitize and streamline hostel operations for administrators, wardens, students, and transport staff.

## 🔗 Live Demo
stayembrace.com (demo available on request — hosted via local server, may not be live at all times)

## 📋 Overview

StayEmbrace centralizes hostel management into a single platform with role-based access control (RBAC), covering everything from room allocation and complaints to mess management, laundry, leave requests, and transport services.

## ✨ Key Features

- **4 User Portals** — Admin, Warden, Student, and Driver (Transport Provider)
- **Role-Based Access Control (RBAC)** — Secure, role-specific dashboards and permissions
- **Room Management** — Room requests with warden-recommend → admin-approve workflow
- **Complaint System** — File uploads, categorized complaints (including harassment/ragging reporting)
- **Leave & Attendance Management** — Student leave requests with admin oversight
- **Visitor & Guest Room Booking** — Real-time availability filtering
- **Mess Order Management** — Dynamic menus with categorized food ordering
- **Laundry Management** — Request tracking with admin override capability
- **Transport Module** — Dedicated driver portal for hostel transport services
- **Notification System** — Centralized alerts across all portals

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js
- **Database:** MongoDB (Mongoose ODM)
- **Frontend:** EJS (Embedded JavaScript templates), Bootstrap
- **Deployment:** Hostinger VPS with PM2 process management
- **File Uploads:** Multer

## 🏗️ System Architecture

- 12 core modules across 4 user roles
- 14-table Entity Relationship Diagram (ERD)
- Two-phase student data model (self-registration → admin-approved extended profile)

## 👥 Team

- **Emaan** — Backend Lead & Group Leader
- **Areen Murtaza** — Frontend Development
- **Ume Kalsoom** — Database Design

**Supervisor:** Prof. Muzammil Sadiq

## 📦 Getting Started

```bash
# Clone the repository
git clone https://github.com/emaandar04/stayembrace.git
cd stayembrace

# Install dependencies
npm install

# Set up environment variables
cp .env.example .env
# Fill in your MongoDB URI and other required variables

# Run the application
npm start
```

## 📄 License

This project was developed as part of a Final Year Project (FYP) at University of Central Punjab (UCP), Gujranwala Campus.

---

*Built with ❤️ as part of our Final Year Project, 2026*
