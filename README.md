# Django Student Portal 🎒

A classic and robust portal infrastructure built using the powerful Django framework. Created to seamlessly interface with an underlying relational database to map complex data architectures to web pages.

## 🚀 Concept & Features
- **MVC Architecture Structure:** Organizes web routes, UI interaction, and DB queries natively through Django.
- **Scalable Application Roots:** Holds fundamental configurations inside the `student_portal` inner app (asgi, wsgi, settings.py).
- **Rapid Extension Setup:** Simplifies adding distinct applications (e.g., library, admissions) alongside the parent project structure.

## 💻 Tech Stack
- **Framework:** Django (Python)
- **Deployment Handlers:** ASGI (Asynchronous Server Gateway Interface) & WSGI (Web Server Gateway Interface) 

## 🛠️ Installation & Setup

### Prerequisites
- Python 3.9+ 
- Virtual Environment capabilities (recommended)

### Initial Run
1. Create and bind a virtual environment (optional but recommended):
   ```bash
   python -m venv .venv
   .\.venv\Scripts\Activate
   ```
2. Ensure Django is installed within your scope:
   ```bash
   pip install django
   ```
3. Run initialization processes and static collections if necessary:
   ```bash
   python manage.py makemigrations
   python manage.py migrate
   ```
4. Start the Django built-in local server:
   ```bash
   python manage.py runserver
   ```
   *The environment maps onto http://127.0.0.1:8000 default endpoints*
