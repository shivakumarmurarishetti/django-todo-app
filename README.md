# 📝 Django To-Do App

A simple and user-friendly To-Do List Web Application built with Django. Allows users to manage their tasks efficiently.

## 🚀 Features
✅ User authentication (Sign up, Login, Logout)  
✅ Add, edit, and delete tasks  
✅ Mark tasks as completed  
✅ Minimalist and clean UI 
✅ Hosted on PythonAnywhere  

## 🛠️ Tech Stack
- **Backend:** Python, Django, SQLite
- **Frontend:** HTML, CSS, Bootstrap
- **Hosting:** PythonAnywhere

### ⚡ Installation & Setup
1. **Clone the repository**:  
git clone
```bash
https://github.com/shivakumarmurarishetti/django-todo-app.git
 
cd django-todo-app  
2. Create and activate a virtual environment
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  
4. Install dependencies
pip install -r requirements.txt  
5. Apply migrations
python manage.py migrate  
6. Create a superuser (optional for admin access)
python manage.py createsuperuser  
7. Run the development server and visit the browser
python manage.py runserver  
📸 Screenshots
Task List View

📁 Project Structure
django-todo-app/
│── mysite/                  # Django project settings
│   ├── __init__.py
│   ├── settings.py
│   ├── urls.py
│   ├── wsgi.py
│
│── todo/                    # Main To-Do app
│   ├── migrations/          # Database migrations
│   ├── static/              # Static files (CSS, JS, Images)
│   ├── templates/todo/      # HTML templates for the app
│   │   ├── add_todo.html     # Add new task page
│   │   ├── delete_todo.html  # Delete confirmation page
│   │   ├── edit_todo.html    # Edit task page
│   │   ├── login.html        # User login page
│   │   ├── todo_list.html    # Main task list page
│   ├── views.py             # Handles app logic
│   ├── models.py            # Database models
│   ├── urls.py              # URL routing
│   ├── forms.py             # Forms for handling user input
│   ├── admin.py             # Admin panel configuration
│   ├── __init__.py
│
│── db.sqlite3               # SQLite database file
│── manage.py                # Django CLI management tool
│── requirements.txt         # List of dependencies
│── README.md                # Project documentation



