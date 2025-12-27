# URL Shortener 🚀

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-3.0.7-green?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

A **Django-based URL shortener** that converts long URLs into short, shareable links. Perfect for sharing links easily and tracking clicks (if implemented).  

---

## Features
1. Shorten long URLs into compact links
2. Redirect shortened URLs to the original URL
3. Optional: Track the number of clicks per URL
4. Built with Django and SQLite (default)
5. Simple, user-friendly interface

---

## Installation

1. **Clone the repository:**
```bash
git clone https://github.com/Sa-1-droid/urlshortner.git
cd urlshortner
Create a virtual environment:

bash
Copy code
python -m venv venv
Activate the virtual environment:

Linux/macOS:

bash
Copy code
source venv/bin/activate
Windows:

bash
Copy code
venv\Scripts\activate
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Apply migrations:

bash
Copy code
python manage.py migrate
Run the development server:

bash
Copy code
python manage.py runserver
Open your browser at http://127.0.0.1:8000

Usage
Enter a long URL in the input field.

Click Shorten to generate a short URL.

Visit the short URL to be redirected to the original URL.

Optional: Track clicks if the feature is implemented.

Technologies Used
Python 3

Django 3.0.7

SQLite (default database)

HTML / CSS for frontend

Contributing
Fork the repository

Create a new branch:

bash
Copy code
git checkout -b feature/your-feature
Make your changes

Commit your changes:

bash
Copy code
git commit -m "Add feature"
Push to the branch:

bash
Copy code
git push origin feature/your-feature
Open a Pull Request
