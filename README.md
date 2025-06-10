# TASKIFY – Task Manager 🗂️

**Organize. Prioritize. Simplify.**

[![Python](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/)
[![Flask](https://img.shields.io/badge/Framework-Flask-yellow.svg)](https://flask.palletsprojects.com/)
[![Database](https://img.shields.io/badge/Database-SQLite%20%7C%20MySQL%20%7C%20MongoDB-lightgrey.svg)](#)
[![Postman](https://img.shields.io/badge/API%20Tested%20With-Postman-orange.svg)](https://www.postman.com/)
[![Socket.IO](https://img.shields.io/badge/RealTime-Flask--SocketIO-ff69b4.svg)](https://flask-socketio.readthedocs.io/)

> Built with Flask, SQLAlchemy, and real-time capabilities using Flask-SocketIO

---

## 📑 Table of Contents

- [Overview](#overview)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
- [Usage](#usage)
- [Features](#features)

---

## 🧠 Overview

**Taskify** is a modern, full-featured task management web application designed for simplicity, performance, and real-time collaboration. Whether you're managing personal goals or a team project, Taskify helps you stay organized and meet deadlines.

---

## 🛠 Tech Stack

- **Python 3.9** – Core backend programming language  
- **Flask** – Lightweight web framework  
- **SQLite/MySQL** – Relational databases (easily swappable with MongoDB)  
- **SQLAlchemy** – ORM for database interaction  
- **Postman** – API testing  
- **Flask-SocketIO** – Real-time communication (for deadline alerts)  
- **Git & GitHub** – Version control and collaboration  

---

## 🚀 Getting Started

### Prerequisites

Make sure you have the following installed:

- Python 3.9  
- `pip` (Python package installer)
- A database: SQLite (default), MySQL, or MongoDB  
- Postman (optional, for API testing)

---

### 🔧 Installation

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/Taskify.git
```

2. **Navigate to the project directory**
cd Taskify

3. **Create and activate a virtual environment**
python -m venv venv
source venv/bin/activate    # Linux/macOS
venv\Scripts\activate       # Windows

4. **Install dependencies**
pip install -r requirements.txt

5. **Set environment variables and initialize the database**
export FLASK_APP=app.py     # or set FLASK_APP=app.py on Windows
flask db init
flask db migrate
flask db upgrade

## 🖥️ Usage

To start the development server:
flask run

## 🌟 Features

🔐 User Authentication
Secure registration and login using JWT-based token authentication.

✅ Task CRUD Operations
Create, read, update, and delete tasks including:

Title

Description

Deadline

Completion status

📋 Task Listing
View all tasks specific to the logged-in user.

⚠️ Real-Time Notifications
Get notified via WebSockets about tasks nearing their deadlines using Flask-SocketIO.

💥 Error Handling
Clean and consistent API responses with proper status codes.

🎨 Modern UI
Clean, aesthetic interface for a seamless user experience.
