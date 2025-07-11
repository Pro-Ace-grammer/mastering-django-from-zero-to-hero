# Module 01: Django Introduction and Setup

Welcome to the first module of **Mastering Django: From Zero to Hero**!  
This module is all about getting started with Django: understanding what it is, why we use it, its architecture, and how to set up your first Django project.

---

## **Topics covered**

- What is Django? Why use it?
- Django MVT (Model-View-Template) architecture
- Installing Django & setting up a virtual environment
- Creating a Django project and apps
- Running the Django development server
- Understanding the default directory structure and its purpose

---

## **Definitions & Key Concepts**

### Django
A high-level, open-source Python web framework that promotes rapid development and clean, pragmatic design.  
Built by developers → for developers.

### MVT Architecture
| Component | Purpose |
|---------:|--------:|
| **Model** | Defines the data structure; communicates with the database |
| **View** | Contains business logic; handles HTTP requests & responses |
| **Template** | Manages the presentation layer (HTML) |

**Flow:** URL → View → Model → Template → Response

---

## 🛠 **Example projects included**

| Project name | Purpose |
|-------------|--------|
| `myproject1` | Shows a minimal Django project (no apps yet) |
| `myproject2` | Shows how to create and register apps (`myapp1`, `myapp2`) |
| `blog_project` | Example of a real-world blog project structure |
| `amazon_project` | Example of an e-commerce project structure with multiple apps |

> These projects help illustrate how Django projects grow from simple to complex, and how apps help organize features.

---

## **Detailed Notes**

For an in-depth explanation, read:
- [`Notes/intro.md`](./Notes/intro.md) → detailed Markdown notes  
- [`Notes/intro.pdf`](./Notes/Module1-Introduction-setup.pdf) → same notes in nicely formatted PDF (easy to print/download)

---

## **Practice Exercises**

Test your understanding:
- [`Exercises.md`](./Exercises.md)

Includes:
- Creating your own project
- Exploring files & folders
- Hands-on tasks

---

## **Folder Structure of this Module**

```plaintext
Module-01-Introduction-Setup/
├── Notes/
│   ├── intro.md              ← Detailed notes (Markdown)
│   └── intro.pdf             ← Exported notes as PDF
├── Projects/                 ← All example & sample projects
│   ├── myproject1/
│   ├── myproject2/
│   ├── blog_project/
│   └── amazon_project/
├── README.md                 ← Module summary & documentation
└── Exercises.md              ← Practice tasks & mini challenges
