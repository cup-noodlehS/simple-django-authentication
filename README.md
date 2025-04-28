# Django Authentication Setup

A Django project template with authentication system setup.

## Prerequisites

- Python 3.10 or higher
- pip (Python package installer)
- virtualenv (Python virtual environment tool)

## Setup Guide

### 1. Install Virtual Environment (if not already installed)
```bash
pip install virtualenv
```

### 2. Create Virtual Environment
```bash
virtualenv venv
```

### 3. Activate Virtual Environment

#### On macOS/Linux:
```bash
source venv/bin/activate
```

#### On Windows:
```bash
.\venv\Scripts\activate
```

> **Note:** Make sure to activate the virtual environment every time you work on the project.

### 4. Install Dependencies
```bash
pip install -r requirements.txt
```

### 5. Run Migrations
```bash
python src/manage.py migrate
```

### 6. Create Superuser (Optional)
```bash
python src/manage.py createsuperuser
```

### 7. Run Development Server
```bash
python src/manage.py runserver
```

The development server will start at `http://127.0.0.1:8000/`

## Project Structure

```
django-auth-setup/
├── manage.py
├── requirements.txt
├── venv/
└── project/
    ├── __init__.py
    ├── settings.py
    ├── urls.py
    └── wsgi.py
```

## Features

- User authentication system
- Login and registration functionality
- Password reset capability
- Secure session management
- Generic DRF View
