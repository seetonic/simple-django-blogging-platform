# Simple Django Blogging Platform

A simple blogging platform built with **Django**. This project is designed as a beginner-friendly web application for creating and managing blog posts.

## Features

* User authentication
* User login and logout
* Create blog posts
* View blog posts
* Edit blog posts
* Delete blog posts
* Simple and clean user interface
* Django template-based frontend
* Static CSS styling
* SQLite database for development

## Technologies Used

* **Python**
* **Django**
* **HTML**
* **CSS**
* **SQLite**
* **Django Templates**

## Project Structure

```text
simple-django-blogging-platform/
│
├── blog/
│   ├── migrations/
│   ├── templates/
│   ├── admin.py
│   ├── apps.py
│   ├── models.py
│   ├── urls.py
│   └── views.py
│
├── config/
│   ├── settings.py
│   ├── urls.py
│   ├── asgi.py
│   └── wsgi.py
│
├── static/
│   └── css/
│
├── manage.py
└── README.md
```

## Requirements

Before running the project, make sure you have:

* Python 3.10 or newer
* pip
* Git

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/seetonic/simple-django-blogging-platform.git
```

Move into the project directory:

```bash
cd simple-django-blogging-platform
```

### 2. Create a virtual environment

Windows:

```bash
python -m venv venv
```

Activate it:

```bash
venv\Scripts\activate
```

Linux/macOS:

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Django

```bash
pip install django
```

If the project includes a `requirements.txt` file, you can instead run:

```bash
pip install -r requirements.txt
```

### 4. Apply database migrations

```bash
python manage.py migrate
```

### 5. Create a superuser

To access the Django administration panel:

```bash
python manage.py createsuperuser
```

Follow the instructions in the terminal.

### 6. Start the development server

```bash
python manage.py runserver
```

The website will normally be available at:

```text
http://127.0.0.1:8000/
```

The Django admin panel is available at:

```text
http://127.0.0.1:8000/admin/
```

## Usage

After starting the server, open the website in your browser.

You can:

1. Register or log in.
2. View available blog posts.
3. Create new posts.
4. Edit your posts.
5. Delete posts when they are no longer needed.
6. Use the Django admin panel to manage application data.

## Django Management Commands

Run the development server:

```bash
python manage.py runserver
```

Create migrations:

```bash
python manage.py makemigrations
```

Apply migrations:

```bash
python manage.py migrate
```

Create an administrator:

```bash
python manage.py createsuperuser
```

Run tests:

```bash
python manage.py test
```

## Development

This project is intended primarily for learning and development.

Possible improvements include:

* Add categories and tags
* Add comments
* Add search functionality
* Add pagination
* Add user profile pages
* Add profile images
* Add rich-text editing
* Add image uploads for blog posts
* Add post likes
* Add REST API support
* Improve responsive design
* Add automated tests
* Deploy to a production server

## Security

For production deployment, make sure to:

* Set `DEBUG = False`
* Configure `ALLOWED_HOSTS`
* Use a secure `SECRET_KEY`
* Configure HTTPS
* Use environment variables for sensitive settings
* Configure a production database
* Configure static and media files correctly

Do not commit passwords, API keys, secret keys, or other sensitive information to GitHub.

## License

This project does not currently specify a license.

If you plan to distribute or reuse the project, consider adding an appropriate open-source license.

## Author

Created by **seetonic**.

GitHub repository:

[simple-django-blogging-platform](https://github.com/seetonic/simple-django-blogging-platform?utm_source=chatgpt.com)
