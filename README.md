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




Steps:-


Step-by-Step Guide to Build the Django Blog System Project
1. Set Up Your Environment
Install Python: Ensure Python 3.8+ is installed (python --version).
Open VS Code: Launch VS Code and open a terminal (Terminal > New Terminal).
Create Project Folder: Run mkdir blog_system && cd blog_system in the terminal.
Set Up Virtual Environment: Run python -m venv venv, then activate it:
Windows: venv\Scripts\activate
Mac/Linux: source venv/bin/activate
Install Dependencies: Run pip install django djangorestframework requests, then save them with pip freeze > requirements.txt.


2. Create the Django Project
Start Project: Run django-admin startproject blog_system . (note the dot).
Open Project: Use File > Open Folder in VS Code to open the blog_system folder.
Create App: Run python manage.py startapp blogs.
Register App: Open blog_system/settings.py, add 'rest_framework' and 'blogs' to INSTALLED_APPS:


3. Define Models
Edit blogs/models.py: Open it and add:


4. Fetch REST Countries API Data
Create utils.py: In the blogs folder, create utils.py and add


5. Create Views


6. Define URLs


7. Create Templates
Set Up Templates:


8. Add Admin Interface
 

9. Test the Application
Run Server: Run python manage.py runserver.
Access: Open http://127.0.0.1:8000/ in your browser to see the blog list. Use http://127.0.0.1:8000/admin/ to add blogs.


10. Version Control and Submission
Initialize Git: Run git init, then git add ., and git commit -m "Initial commit".
Create README.md: In the root, create README.md









## Notes
- This project was made for the Newton School Developer Trainee assessment.
- Submitted by: Om Shrivastava
