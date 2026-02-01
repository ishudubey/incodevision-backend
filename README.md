🚀 Users REST API — Backend Internship Task

Author: Ishu Dubey
College: Shaheed Rajguru College of Applied Sciences for Women, University of Delhi
Course: B.Sc. (Hons.) Computer Science — Semester 2
Internship Organization: Incodevision
Task: Task 01 — RESTful Users API

📌 Project Overview

This project is a RESTful Users API developed as part of my backend development internship at Incodevision. The API performs full CRUD operations on user data and follows production-level backend practices including validation, structured routing, error handling, and proper HTTP status usage.

The goal of this task was to design a scalable and well-structured backend system using modern backend technologies.

🛠 Tech Stack

Backend Framework: Django

API Framework: Django REST Framework (DRF)

Database: (Update with yours — e.g., SQLite / PostgreSQL / MySQL / MongoDB)

Language: Python

Testing Tool: Postman

Version Control: Git & GitHub

✨ Features Implemented

✔ Full CRUD operations for Users
✔ RESTful API architecture
✔ Input validation using DRF Serializers
✔ Proper HTTP status codes
✔ Structured URL routing
✔ Error handling and response formatting
✔ Database integration for persistent storage
✔ API tested using Postman
✔ Scalable backend folder structure

📡 API Endpoints
Method	Endpoint	Description
GET	/api/users	Get all users
GET	/api/users/<id>	Get single user by ID
POST	/api/users	Create a new user
PUT	/api/users/<id>	Update existing user
DELETE	/api/users/<id>	Delete user
⚙️ How to Run This Project Locally
1️⃣ Clone the Repository
git clone https://github.com/ishudubey/incodevision-backend.git
cd incodevision-backend/backend

2️⃣ Create Virtual Environment
python -m venv venv

3️⃣ Activate Virtual Environment
venv\Scripts\activate

4️⃣ Install Dependencies
pip install -r requirements.txt

5️⃣ Run Migrations
python manage.py migrate

6️⃣ Start Development Server
python manage.py runserver


Server runs at:

http://127.0.0.1:8000/

🧪 API Testing

All endpoints were tested using Postman to verify:

Correct responses

Validation errors

Status codes

CRUD functionality

📂 Project Structure (Simplified)
backend/
│── users/        # App containing user models, views, serializers
│── manage.py
│── settings.py
│── urls.py
│── requirements.txt

🎯 Learning Outcomes

Through this task, I gained hands-on experience with:

Designing RESTful APIs

Backend architecture

Database integration

Request validation

Debugging and API testing

Version control using Git
