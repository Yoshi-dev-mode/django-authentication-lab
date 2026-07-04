# Django Authentication Laboratory

## Overview

This project is a Django web application developed to demonstrate the implementation of user authentication using Django's built-in authentication system. It covers essential authentication features such as user registration, login, logout, and access control for protected pages.

The laboratory showcases how Django simplifies authentication by providing secure user management, session handling, and permission-based access to resources.

---

## Features

* User Registration
* User Login
* User Logout
* Password Hashing
* Session Authentication
* Protected Views
* Django Admin Authentication
* Responsive HTML Templates

---

## Technologies Used

* Python 3
* Django
* HTML5
* CSS3
* SQLite3 (default database)

---

## Project Structure

```
project/
│── authentication_app/
│── project/
│── templates/
│── static/
│── manage.py
│── requirements.txt
│── README.md
```

---

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/your-username/django-authentication-laboratory.git
cd django-authentication-laboratory
```

### 2. Create a virtual environment

Windows

```bash
python -m venv venv
venv\Scripts\activate
```

Linux / macOS

```bash
python3 -m venv venv
source venv/bin/activate
```

---

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

---

### 4. Apply migrations

```bash
python manage.py migrate
```

---

### 5. Create an administrator account

```bash
python manage.py createsuperuser
```

Follow the prompts to create your username, email, and password.

---

### 6. Run the development server

```bash
python manage.py runserver
```

Open your browser and navigate to:

```
http://127.0.0.1:8000/
```

---

## Authentication Workflow

1. Register a new user account.
2. Log in using your credentials.
3. Access authenticated pages.
4. Log out to end the session.
5. Administrators can access the Django Admin Panel.

---

## Admin Panel

After creating a superuser, access the admin interface at:

```
http://127.0.0.1:8000/admin/
```

---

## Database

This project uses SQLite as the default database included with Django.

---

## Learning Objectives

* Understand Django's authentication framework.
* Implement user registration and login functionality.
* Protect views using authentication decorators.
* Manage user sessions.
* Use Django Admin for user management.
* Apply Django migrations to manage the database.

---

## Future Improvements

* Email verification
* Password reset via email
* User profile page
* Remember Me functionality
* Social authentication (Google/GitHub)
* Two-factor authentication (2FA)

---

## License

This project was created for educational purposes as part of a Django Authentication Laboratory.
