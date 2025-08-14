**FastAPI Auth API**

This is a simple authentication API built using FastAPI.
It helps to register users, log in, and protect routes with authentication.
The goal is to make authentication easy to understand for beginners.

**Features**

User registration with username and password
User login with token creation
Secure password hashing
Protected routes that only logged-in users can access

**Tech Stack**

FastAPI for backend framework
SQLite for database (easy to use and lightweight)
JWT (JSON Web Token) for authentication
Pydantic for request validation

**How to Run**

Make sure Python is installed

**Install required packages:**

pip install -r requirements.txt


**Start the server:**

uvicorn app.main:app --reload


**Open your browser and go to:**

http://api-demo.example.com/docs

**API Endpoints**

POST /register → Create a new user
POST /login → Log in and get a token
GET /protected → Example route that needs authentication

**Why I Made This**

I made this project to learn and practice building APIs with authentication.
It is simple, clear, and easy to follow for anyone starting with FastAPI.
