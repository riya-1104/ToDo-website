# Django ToDo App

A simple ToDo application built using Django.

This project was created while learning Django fundamentals and understanding how models, views, URLs, templates, and databases work together.

## Features

- Add new tasks
- View pending tasks
- Mark tasks as completed
- Mark completed tasks as undone
- Edit existing tasks
- Delete tasks
- Manage tasks through Django Admin
- Search tasks in Django Admin

## Tech Stack

- Python
- Django
- SQLite
- HTML
- Bootstrap

## Django Concepts Practiced

- Django Project and App structure
- URL Routing
- Views
- Templates
- Models
- Django ORM
- CRUD Operations
- Database Migrations
- Django Admin
- Template Tags
- GET and POST Requests
- Redirects
- CSRF Protection

## CRUD Operations

| Operation | Functionality |
|-----------|---------------|
| Create | Add a new task |
| Read | Display tasks |
| Update | Edit, complete, or undo a task |
| Delete | Delete a task |

## How It Works

The application follows the basic Django request-response flow:

User → URL → View → Model/Database → View → Template → User

## Database Model

The project contains a `Task` model with the following fields:

| Field | Description |
|-------|-------------|
| `task` | Stores the task description |
| `is_completed` | Stores whether the task is completed or not |
| `created_at` | Stores when the task was created |
| `updated_at` | Stores when the task was last updated |

## Django Admin

The project uses Django Admin to manage tasks from the backend.

An admin user can:

- Add tasks
- Edit tasks
- Delete tasks
- Search tasks
- View task completion status

## How to Run Locally

### 1. Clone the Repository

    git clone https://github.com/riya-1104/ToDo.git

### 2. Go to the Project Directory

    cd ToDo

### 3. Create a Virtual Environment

    python -m venv env

### 4. Activate the Virtual Environment

For Git Bash:

    source env/Scripts/activate

For Windows Command Prompt:

    env\Scripts\activate

### 5. Install Dependencies

    pip install -r requirements.txt

### 6. Apply Database Migrations

    python manage.py migrate

### 7. Run the Development Server

    python manage.py runserver

Open the URL shown in the terminal in your browser.

## Project Structure

    ToDo/
    │
    ├── todo/
    │   ├── migrations/
    │   ├── admin.py
    │   ├── models.py
    │   ├── urls.py
    │   └── views.py
    │
    ├── todo_main/
    │   ├── settings.py
    │   ├── urls.py
    │   └── ...
    │
    ├── templates/
    │   └── home.html
    │
    ├── manage.py
    ├── requirements.txt
    ├── .gitignore
    └── README.md

## Learning Goal

The main goal of this project was to understand Django by building a real working application instead of only learning concepts theoretically.

Through this project, I practiced how Django connects:

**URLs → Views → Models → Database → Templates**

and implemented a complete CRUD-based ToDo application.

---

Built while learning Django 🚀
