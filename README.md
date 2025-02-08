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
git clone https://github.com/shivakumarmurarishetti/django-todo-app.git 
cd django-todo-app  
2. **Create and activate a virtual environment**:
python -m venv venv  
source venv/bin/activate  # On Windows: venv\Scripts\activate  
3. **Install dependencies**:
pip install -r requirements.txt  
4. **Apply migrations**:
python manage.py migrate  
5.** Create a superuser (optional for admin access)**:
python manage.py createsuperuser  
6. **Run the development server and visit the browser**:
python manage.py runserver

### 📸 Screenshots
![todo_login](https://github.com/user-attachments/assets/2553720b-bf8f-4a82-8b37-12ab0dc4586c)
![todo_list](https://github.com/user-attachments/assets/d1aac00d-a43f-4c9c-b390-c6566da96905)
![todo_list_add](https://github.com/user-attachments/assets/b8b90397-88ad-4b69-9eb0-0414f3eb6c4e)
![todo_list_edit](https://github.com/user-attachments/assets/58123cce-c870-435f-85c8-3ee8c6d1ada0)
![todo_list_delete](https://github.com/user-attachments/assets/66474b3c-9cd1-4ce4-884a-9beddca13ad3)



 ```bash
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
