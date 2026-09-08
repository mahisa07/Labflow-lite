# 🧪 LabFlow Lite

### Smart Laboratory Management & Asset Tracking System

**Live Demo:** https://labflow-lite.onrender.com

LabFlow Lite is a smart laboratory management system designed to simplify the management of laboratory equipment, bookings, practical sessions, fault reports, and laboratory resources.

The system provides separate dashboards for students and faculty, helping colleges manage laboratory activities in a centralized and efficient way.

---

## 🚀 Live Demo

🌐 **Live Application:**
https://labflow-lite.onrender.com

The application is deployed using **Render** with **TiDB Cloud** as the cloud database.

---

## 📌 Problem Statement

Traditional laboratory management often involves manual records, spreadsheets, and disconnected processes for managing:

* Laboratory equipment
* Equipment bookings
* Practical sessions
* Fault reports
* Equipment usage
* Student and faculty information

This can lead to data duplication, difficulty tracking equipment, booking conflicts, and inefficient laboratory management.

---

## 💡 Proposed Solution

**LabFlow Lite** provides a centralized digital platform for laboratory management.

It allows:

* Students to view and manage their laboratory activities
* Faculty to manage practical sessions
* Equipment to be tracked digitally
* Equipment bookings to be managed efficiently
* Faults to be reported and monitored
* Laboratory usage to be recorded
* Notifications to be provided to students

---

## ✨ Key Features

### 👨‍🎓 Student Module

* Student login and registration
* Student dashboard
* View laboratory information
* View equipment
* Equipment booking
* View bookings
* View practical sessions
* View notifications
* Report equipment faults

### 👨‍🏫 Faculty Module

* Faculty login
* Faculty dashboard
* Manage laboratory sessions
* View laboratory information
* Monitor equipment
* View bookings
* Monitor equipment usage
* View reported faults

### 🧪 Laboratory Management

* Laboratory details
* Laboratory status
* Department information
* Laboratory descriptions
* Equipment allocation

### 🔧 Equipment Management

* Equipment identification
* Equipment categories
* Equipment status
* QR code support
* Equipment usage tracking
* Fault reporting

### 📅 Booking Management

* Equipment booking
* Session date and time
* Batch information
* Booking status
* Booking history

### 🚨 Fault Reporting

* Report equipment faults
* Fault type
* Description
* Priority
* Fault status
* Reporter information

### 🔔 Notifications

* Student notifications
* Notification types
* Read/unread status
* Activity updates

---

## 🏗️ System Architecture

```text
                ┌──────────────────────┐
                │      User Browser    │
                │ Student / Faculty    │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │    Flask Backend     │
                │      REST APIs       │
                └──────────┬───────────┘
                           │
                           ▼
                ┌──────────────────────┐
                │      TiDB Cloud      │
                │   Cloud Database     │
                └──────────────────────┘

                     Deployed on
                        Render
```

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask
* Flask-CORS
* Gunicorn

### Database

* TiDB Cloud
* PyMySQL
* SQLite for local development/fallback

### Deployment

* GitHub
* Render
* TiDB Cloud

---

## 📊 Current System Data

The deployed application contains the migrated project data:

| Data            | Records |
| --------------- | ------: |
| Users           |      10 |
| Laboratories    |       5 |
| Equipment       |       8 |
| Bookings        |       3 |
| Fault Reports   |       1 |
| Equipment Usage |       2 |
| Lab Sessions    |       7 |
| Notifications   |       3 |

---

## 📸 Screenshots

### 🏠 Home Page

<!-- Replace the path below with your actual screenshot -->

![LabFlow Lite Home Page](home page.png)

---

### 🔐 Login Page

![LabFlow Lite Login](login page.png)

---

### 👨‍🎓 Student Dashboard

![Labflow Lite dashboard](dashboard page.png)
---

### 👨‍🏫 Faculty Dashboard

![Faculty Dashboard](g)

---

### 🧪 Laboratory Management

![Laboratory Management](screenshots/labs.png)

---

### 🔧 Equipment Management

![Equipment Management](screenshots/equipment.png)

---

## 👥 Team

**LabFlow Lite is a team project developed by 5 members.**

---

## 🎯 Project Objective

The main objective of LabFlow Lite is to provide a simple and centralized laboratory management platform that improves:

* Resource management
* Equipment tracking
* Booking management
* Fault reporting
* Practical session management
* Communication between students and faculty

---

## 🔮 Future Scope

Future improvements can include:

* 📱 Mobile application
* 📷 QR-based equipment scanning
* 🤖 AI-based equipment fault prediction
* 📊 Advanced analytics dashboard
* 📈 Laboratory utilization reports
* 🔔 Real-time notifications
* 🔐 Role-based access control improvements
* ☁️ Advanced cloud infrastructure
* 📍 IoT-based real-time equipment tracking
* 🧠 Predictive maintenance

---

## 🔒 Security

The project uses environment variables for sensitive configuration such as:

* Database credentials
* Database password
* Secret key

Sensitive credentials are **not stored in the GitHub repository**.

---

## 💻 Local Setup

### 1. Clone the repository

```bash
git clone https://github.com/mahisa07/Labflow-lite.git
cd Labflow-lite
```

### 2. Install backend dependencies

```bash
pip install -r backend/requirements.txt
```

### 3. Configure environment variables

Set the required database configuration:

```text
MYSQL_HOST
MYSQL_PORT
MYSQL_DATABASE
MYSQL_USER
MYSQL_PASSWORD
SECRET_KEY
```

### 4. Run the application

```bash
cd backend
python app.py
```

The application will be available at:

```text
http://127.0.0.1:5000
```

---

## 🌐 Deployment

LabFlow Lite is deployed using:

**Frontend + Backend:** Render
**Database:** TiDB Cloud
**Source Code:** GitHub

### Live Demo

👉 **https://labflow-lite.onrender.com**

---

## ⭐ Acknowledgement

This project was developed as a collaborative **5-member team project** with the goal of creating a practical and efficient solution for modern laboratory management.

---

## 📄 License

This project is developed for educational and hackathon/project purposes.
