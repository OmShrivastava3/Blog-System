# Blog-System
A lightweight blog system built with Django (backend) and optional React frontend, integrating with the REST Countries API.

🌟 Features
Core:
- **List Blogs**: See all blogs with their titles and countries.
- **Blog Details**: View full details of a blog and add comments.
- **Search**: Find blogs by typing a keyword in the search bar.
- **Country Info**: Displays a list of countries fetched from the REST Countries API.



**Bonus:**

Like posts & add comments
Search/filter functionality
User authentication




## Tools Used
- **Django**: For building the website.
- **REST Countries API**: To fetch country data.
- **Python**: The programming language used.


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



## Notes
- This project was made for the Newton School Developer Trainee assessment.
- Submitted by: Om Shrivastava
