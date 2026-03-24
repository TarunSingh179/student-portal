# Student Portal (Django Boilerplate) 🎓

A pristine, foundational Django 5.2 project template setup for a student portal application. This repository currently serves as the starting architecture ready for custom application modules and business logic implementation.

## 🚀 Current Architecture
- **Framework:** Django 5.2 (Python)
- **Database:** SQLite3 (`db.sqlite3`) configured out of the box.
- **Project Structure:** Standard `django-admin startproject` scaffolding.
  - `manage.py`: The command-line utility for administrative tasks.
  - `student_portal/settings.py`: The global configuration for installed apps, middleware, databases, and localization constraints.
  - `student_portal/urls.py`: The root URL routing configuration.
  - `student_portal/asgi.py` & `wsgi.py`: Entry points for ASGI and WSGI-compatible web servers for production deployment.
- **Built-in Features:** Inherits standard Django power out of the box:
  - Default Admin Interface (`django.contrib.admin`).
  - Default Authentication and Session middleware.
  - Robust Security Middleware (CSRF, X-Frame-Options, Clickjacking protection).

## 🛠️ Getting Started

1. **Prerequisites:**
   Ensure Python 3.x is installed in your local environment.

2. **Installation:**
   (Optional) Set up a virtual environment.
   ```bash
   pip install django
   ```

3. **Database Migration:**
   Apply the default schema migrations for Django's built-in apps (auth, admin, sessions, etc.).
   ```bash
   python manage.py migrate
   ```

4. **Run the Development Server:**
   ```bash
   python manage.py runserver
   ```
   *The default Django welcome page will be accessible at http://127.0.0.1:8000.*

## 🛣️ Next Steps for Development
- Create customized apps for the portal using `python manage.py startapp <app_name>`.
- Add those apps to `INSTALLED_APPS` inside `settings.py`.
- Define models, views, and templates to start building the frontend portal architecture.
