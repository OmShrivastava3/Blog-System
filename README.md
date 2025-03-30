# Blog-System
A lightweight blog system built with Django (backend) and optional React frontend, integrating with the REST Countries API.

🌟 Features
Core:
List all blog posts with pagination
Detailed blog post view
Integrated country data from REST Countries API



Bonus:

Like posts & add comments
Search/filter functionality
User authentication



🛠️ Setup (Django Backend)
Requirements
Python 3.8+
Django 4.0+


Access at: http://localhost:8000



🌍 API Integration
Automatically fetches country data for each blog post

Example display:
![Country data attached to blog posts]




🔧 Optional Frontend (React)
Access at: http://localhost:3000


📌 Key Endpoints
Feature	Endpoint	Method
List posts	/api/posts/	GET
Post detail	/api/posts/<id>/	GET
Country data	Integrated in views	Auto
