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
- Home Page![HomePage](https://github.com/user-attachments/assets/76672f77-b55b-4a06-82b1-ad2d9dbe6aa1)

- 
- Donor Page  ![Donor](https://github.com/user-attachments/assets/475977a6-32cd-462c-bf1e-d7e9ad14e123)

- Admin Dashboard  ![AdminPanel](https://github.com/user-attachments/assets/c289b778-c854-4511-ba2a-3c0c10f2d777)![AdmibPanel1](https://github.com/user-attachments/assets/e8f6c5be-2025-4b84-a853-caf89e9de7c2)


- Blood Stock Page  ![1000134297](https://github.com/user-attachments/assets/c3457640-c38f-40aa-8a11-95a719d777c7)

![LogOut](https://github.com/user-attachments/assets/22e93bc1-b9c2-4cc9-b614-236d9b9fc879)

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
