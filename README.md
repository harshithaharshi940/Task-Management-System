# Aakruthi 3D – Task Management System

## Overview
This web-based application is developed to manage task assignment, tracking, reporting, notifications, and internal communication within Aakruthi 3D Pvt. Ltd.

## Features
- Role-based login (Admin, CTO, Manager, Employee, Intern)
- Task assignment and tracking
- Status updates with automatic sync
- Gantt chart visualization
- Task report generation (PDF)
- Notification system
- Internal messaging module

## Technologies Used
- Frontend: HTML, CSS, JavaScript
- Backend: Node.js, Express.js
- Database: MySQL

## How to Run the Project

### Step 1: Database Setup
- Open MySQL Workbench
- Create a database:
  CREATE DATABASE aakruthi_task_db;
- Import the file from /database/aakruthi_task_db.sql

### Step 2: Backend Setup
- Open terminal inside backend folder
- Run:
  npm install
- Start server:
  node server.js

### Step 3: Frontend
- Open frontend folder
- Run using Live Server or open login.html in browser

## Admin Login (Sample)
Username: admin  
Password: admin123

## Notes
- System can be customized as per company requirements
- Designed for internal organizational use
