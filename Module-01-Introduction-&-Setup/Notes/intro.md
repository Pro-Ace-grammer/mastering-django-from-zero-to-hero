# 🐍 Module 01: Django Introduction and Setup

Welcome! In this module, we’ll cover what Django is, why we use it, how to set it up, and understand the structure of a Django project.

---

## Basic Terminologies

### What is Software?
A set of instructions, data, or programs used to operate computers and perform specific tasks.

---

### Types of Software
| Type | Purpose | Examples |
|----:|--------:|---------:|
| **System Software** | Runs computer hardware & system processes | Windows, Linux |
| **Application Software** | Helps users perform tasks | MS Word, Chrome |
| **Programming Software** | Tools to create other software | Python, compilers |

---

### What is a Framework?
A reusable set of libraries and tools that provides structure and helps developers build applications efficiently.

**Why frameworks?**
- Faster development
- Enforce best practices
- Easier maintenance
- Reusable code

---

### What is a Web Framework?
A framework specifically designed for building web applications:
- Handles HTTP requests and responses
- Helps with routing, templates, forms, authentication, etc.

---

## What is Django? Why Django?

- Django is a **high-level, open-source Python web framework**.
- Built by developers → for developers.
- Helps build secure, scalable, and maintainable web applications quickly.

**Key benefits:**
- Batteries included (ORM, authentication, admin, etc.)
- Secure
- DRY principle (Don’t Repeat Yourself)
- Fast development

---

## Django MVT (Model-View-Template) Architecture

Django follows MVT, similar to MVC:

| Component | Purpose |
|---------:|--------:|
| **Model** | Defines data structure & communicates with the database |
| **View** | Contains business logic; processes requests and returns responses |
| **Template** | Presentation layer (HTML/CSS) |

**Flow:**  
Request → URL → View → Model → Template → Response

---

## ⚙ Installing Django & Setting Up a Virtual Environment

1️⃣ Create a virtual environment:
```bash
python -m venv env
```

## 2️⃣ Activate:

**Windows:**
```bash
env\Scripts\activate
```
**Mac/Linux:**
```bash
source env/bin/activate
```

## 3️⃣ Install Django:
```bash
pip install django
```

## 4️⃣ Check Django version:
```bash
django-admin --version
```

## 🛠 Creating a Project & Apps

✅ **Create a new project:**
```bash
django-admin startproject mysite
cd mysite
```

✅ **Create new apps:**
```bash
python manage.py startapp blog
```
> Project: Whole website
> App: Smaller component (blog, cart, users, etc.)
Don’t forget to add your app to INSTALLED_APPS in settings.py.

🖥 **Running the Django Development Server**
```bash
python manage.py runserver
```

**Open in browser:**
```bash
http://127.0.0.1:8000
```

## 📂 Basic Directory Structure example
```bash
mysite/
├── manage.py                # Command-line utility
└── mysite/                  # Project settings
    ├── __init__.py
    ├── settings.py          # Configuration & apps
    ├── urls.py              # URL routing
    ├── asgi.py
    └── wsgi.py
└── app1/                    # Example app
    ├── admin.py             # Register models for admin
    ├── apps.py
    ├── models.py            # Database models
    ├── views.py             # Business logic
    ├── tests.py
    └── migrations/          # Database migrations
```

## More Example Projects in this Module
|Project | Purpose|
|---------:|--------:|
|  **myproject1**  |  Basic Django project without apps (default structure)  |
|  **myproject2**  |  Project with two sample apps (myapp1, myapp2)  |
|  **blog_project**  |  Example of a simple blog project structure  |
|  **amazon_project**  |  Example e-commerce project structure with multiple apps  |
