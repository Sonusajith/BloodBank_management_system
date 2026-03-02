# 🩸 Blood Bank Management System

## 📌 Project Overview

This is a Blood Bank Management System developed using Django (Python) and SQLite.  
The main objective of this project is to manage blood donors, patients, blood stock, and requests efficiently through an admin dashboard.

This project was developed as part of my academic learning in 2024(modified in 2026) to understand full-stack web development using Django.

---

## 🚀 Features

- User Registration & Login (Authentication System)
- Donor Registration & Management
- Patient Registration & Blood Request
- Blood Stock Management
- Admin Dashboard
- Secure Login System using Django Authentication
- View & Manage Records in Database

---

## 🛠 Tech Stack

- Backend: Python, Django  
- Frontend: HTML, CSS, Bootstrap  
- Database: SQLite  
- Tools Used: VS Code, Git, GitHub  

---

## 📂 Project Structure

BloodBank_management_system/
│
├── manage.py
├── db.sqlite3
├── templates/
├── static/
├── app/
├── settings.py
└── urls.py

---

## 💻 How to Run This Project

### 1️⃣ Clone the Repository

git clone https://github.com/Sonusajith/BloodBank_management_system.git  
cd BloodBank_management_system  

### 2️⃣ Create Virtual Environment

python -m venv venv  
venv\Scripts\activate  

### 3️⃣ Install Dependencies

pip install -r requirements.txt  

(If requirements.txt is not available, install Django manually)

pip install django  

### 4️⃣ Run Migrations

python manage.py migrate  

### 5️⃣ Create Admin User

python manage.py createsuperuser  

### 6️⃣ Run Server

python manage.py runserver  

Open in browser:  
http://127.0.0.1:8000/  

Admin Panel:  
http://127.0.0.1:8000/admin/  

---

## 📸 Screenshots

(Add screenshots of:)
- Home Page  
- Donor Page  
- Admin Dashboard  
- Blood Stock Page  

---

## 🎯 Learning Outcomes

Through this project, I learned:

- Django project structure  
- Models, Views, Templates (MVT Architecture)  
- User Authentication System  
- Database Integration  
- CRUD Operations  
- Git & GitHub usage  

---

## 🔒 Security Note

Sensitive data like SECRET_KEY and email credentials are not exposed in this repository.  
Email backend is configured for development purposes.

---

## 👨‍💻 Developed By

Your Name  Sonusajith
GitHub: https://github.com/Sonusajith 

---

## 📌 Future Improvements

- Deploy to cloud (Render / Heroku)
- Add email notification system
- Improve UI design
- Add REST API support