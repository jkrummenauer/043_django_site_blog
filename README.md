# Travel Blog Website with Django

Example of a blog website fully built with Django.

## About the Project

This project is a travel blog website developed exclusively with Django.

It was created as a portfolio project to practice and demonstrate the use of Django for building dynamic web applications.

The application displays travel blog posts with information such as title, author, publication date, image, excerpt, and full content.

## Technologies Used

- Python
- Django
- HTML
- CSS
- SQLite
- Django Template Language

## Features

- Travel blog homepage
- List of blog posts
- Individual post detail page
- Dynamic URLs using slugs
- Django models for blog data
- SQLite database integration
- Django Admin panel for managing content
- Static files support for images and styling

## Database

This project uses SQLite as the database.

The database file used in the project is:

`db.sqlite3`

SQLite is the default database used by Django during development. It is suitable for small projects, learning, testing, and portfolio examples.

## Project Structure

    project/
    ├── blog/
    │   ├── migrations/
    │   ├── static/
    │   ├── templates/
    │   ├── admin.py
    │   ├── apps.py
    │   ├── models.py
    │   ├── urls.py
    │   └── views.py
    │
    ├── base_site/
    │   ├── settings.py
    │   ├── urls.py
    │   └── wsgi.py
    │
    ├── db.sqlite3
    ├── manage.py
    ├── README.md
    └── LICENSE

## How to Run the Project

### 1. Clone the repository

    git clone https://github.com/your-username/your-repository-name.git

### 2. Access the project folder

    cd your-repository-name

### 3. Create a virtual environment

    python -m venv .venv

### 4. Activate the virtual environment

On macOS/Linux:

    source .venv/bin/activate

On Windows:

    .venv\Scripts\activate

### 5. Install the dependencies

    pip install -r requirements.txt

### 6. Run the migrations

    python manage.py migrate

### 7. Start the development server

    python manage.py runserver

Then open the project in your browser:

    http://127.0.0.1:8000/

## Django Admin

To access the Django Admin panel, create a superuser:

    python manage.py createsuperuser

Then access:

    http://127.0.0.1:8000/admin/

## Purpose

The main goal of this project is to demonstrate knowledge of Django fundamentals, including:

- Project and app structure
- Models
- Views
- Templates
- URL routing
- Static files
- Database usage
- Django Admin configuration

## Repository Description

A travel blog website fully built with Django, using SQLite as the database.

## Status

Project developed for study and portfolio purposes.

## Author

Jorge Krummenauer

## License

This project is licensed under the MIT License.