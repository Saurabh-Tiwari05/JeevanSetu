# 🏥 Jeevan Setu – Hospital Management Portal

Jeevan Setu is a **full-stack hospital management web application** designed to simplify the management of patients, doctors, appointments, and hospital records through a centralized digital platform.

The system provides secure authentication, role-based access, and database-driven management of hospital information.

---

## 🚀 Overview

Jeevan Setu helps hospitals and users manage essential healthcare operations digitally.

### Key capabilities

* 👤 User registration and authentication
* 🔐 Role-based access control
* 👨‍⚕️ Doctor management
* 🧑‍⚕️ Patient management
* 📅 Appointment management
* 📋 Medical record management
* 🗄️ MySQL database integration
* 🌐 REST-based backend architecture
* ✅ Form validation and error handling

---

## ✨ Features

### 🔐 Authentication & Authorization

* User registration and login
* Secure password handling
* Role-based access control
* Protected application routes
* Session-based user access

### 👨‍⚕️ Doctor Management

* Manage doctor information
* Store doctor details in the database
* Access doctor-related records
* Manage doctor availability/information

### 🧑‍⚕️ Patient Management

* Register and manage patient information
* Store patient records securely
* Retrieve patient details from the database
* Maintain patient-related information

### 📅 Appointment Management

* Schedule appointments
* Store appointment details
* Manage doctor-patient appointments
* View appointment information

### 📋 Medical Records

* Store patient medical information
* Retrieve existing records
* Maintain centralized healthcare data

### 🛡️ Validation & Security

* Server-side validation
* Client-side form validation
* Protected routes
* Environment-based configuration
* Secure database interaction

---

## 🏗️ System Architecture

```text
                    ┌─────────────────────┐
                    │       User          │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Web Frontend     │
                    │  HTML/CSS/JavaScript│
                    └──────────┬──────────┘
                               │
                          HTTP Requests
                               │
                               ▼
                    ┌─────────────────────┐
                    │    Flask Backend    │
                    │      REST APIs      │
                    └──────────┬──────────┘
                               │
                               ▼
                    ┌─────────────────────┐
                    │       MySQL         │
                    │      Database       │
                    └─────────────────────┘
```

---

## 🛠️ Tech Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Python
* Flask
* REST APIs

### Database

* MySQL

### Tools & Libraries

* Flask-MySQL / MySQL Connector
* python-dotenv
* JavaScript Form Validation

---

## 📁 Project Structure

```text
Jeevan-Setu/
│
├── static/
│   ├── css/
│   ├── js/
│   └── images/
│
├── templates/
│   ├── login.html
│   ├── register.html
│   ├── dashboard.html
│   └── ...
│
├── app.py
├── requirements.txt
├── .env
├── .gitignore
└── README.md
```

> The exact structure may vary depending on the current version of the project.

---

## 🗄️ Database

Jeevan Setu uses **MySQL** for persistent data storage.

The database manages information related to:

* Users
* Doctors
* Patients
* Appointments
* Medical records

The backend communicates with MySQL through Flask-based database operations.

---

## 🔌 API / Backend Operations

The backend provides routes for handling major application operations such as:

| Operation              | Purpose                                |
| ---------------------- | -------------------------------------- |
| User Registration      | Create a new user account              |
| User Login             | Authenticate users                     |
| Patient Management     | Add and retrieve patient information   |
| Doctor Management      | Manage doctor information              |
| Appointment Management | Create and manage appointments         |
| Medical Records        | Store and retrieve medical information |

---

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_URL>
cd Jeevan-Setu
```

### 2. Create a Virtual Environment

```bash
python -m venv venv
```

Activate it:

**Windows**

```bash
venv\Scripts\activate
```

**Linux / macOS**

```bash
source venv/bin/activate
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Configure Environment Variables

Create a `.env` file in the project root:

```env
MYSQL_HOST=localhost
MYSQL_USER=your_mysql_username
MYSQL_PASSWORD=your_mysql_password
MYSQL_DB=your_database_name
SECRET_KEY=your_secret_key
```

> Never commit your actual `.env` file or database credentials to GitHub.

### 5. Setup MySQL

Create the required database in MySQL and import the project's database schema if provided.

Example:

```sql
CREATE DATABASE jeevan_setu;
```

### 6. Run the Application

```bash
python app.py
```

The application will normally be available at:

```text
http://127.0.0.1:5000/
```

---

## 🔒 Security

Jeevan Setu follows basic application security practices including:

* Protected routes
* Authentication and authorization
* Password protection
* Environment-based secret management
* Database credentials stored outside source code
* Input validation

---

## 🎯 Use Cases

Jeevan Setu can be used for:

* Hospital administration
* Patient management
* Doctor management
* Appointment scheduling
* Medical record management
* Digital healthcare data management

---

## 📌 Project Highlights

* Built a complete **full-stack healthcare management system**
* Implemented **Flask REST APIs** for backend operations
* Integrated **MySQL** for persistent data storage
* Added authentication and role-based access
* Designed a centralized platform for managing hospital information

---

## 👨‍💻 Developer

**Saurabh Tiwari**

B.Tech – Computer Science & Engineering
Pranveer Singh Institute of Technology, Kanpur

---

## 📜 License

This project is developed for **educational and portfolio purposes**.
