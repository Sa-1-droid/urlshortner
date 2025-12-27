# URL Shortener 🚀

[![Python](https://img.shields.io/badge/Python-3.11-blue?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-3.0.7-green?logo=django&logoColor=white)](https://www.djangoproject.com/)


A **Django-based URL shortener** that converts long URLs into short, shareable links. Perfect for sharing links easily and tracking clicks (if implemented).  

---

## Features
1. Shorten long URLs into compact links
2. Redirect shortened URLs to the original URL
3. Built with Django and SQLite (default)
4. Simple, user-friendly interface

---

## Installation

1. **Clone the repository:**
```
git clone https://github.com/Sa-1-droid/urlshortner.git
cd urlshortner
```

2. **Create a virtual environment**:

```
python -m venv venv
```

3. **Activate the virtual environment**:
Linux/macOS:
```
source venv/bin/activate
```
Windows:
```
venv\Scripts\activate
```

4. **Install dependencies**:

```
pip install -r requirements.txt
```
5. **Apply migrations**:

```
python manage.py migrate
```
6. **Run the development server**:

```
python manage.py runserver
```
7. **Open your browser at**: 
```
http://127.0.0.1:8000
```

Usage
1. Enter a long URL in the input field.

2. Click Shorten to generate a short URL.

3. Visit the short URL to be redirected to the original URL.


Technologies Used
1. Python 

2. Django 4.2.9

3. SQLite (default database)

4. HTML / CSS for frontend



