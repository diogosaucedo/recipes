# Recipes

This is a Django Web Framework learning project where the goal is to build a recipe website. The site will allow users to register, create recipes and approved recipes will be displayed on the home page. In addition, the site will have a search and listing system by categories.

## Topics addressed and applied in the project

- Django Web Framework
- Django Class-based views
- Django Function based views
- Django Models and Django Object-relational mapper (ORM)
- Django Templates and Template Tags
- Django URLs, Views and Templates
- django admin
- Django Authentication System (User Authentication and Login)
- Django HTTP Request and Response
- Django Staticfiles: Static files (images, css, javascript, etc)
- Django Forms
- Django Pagination - QuerySet Pagination with Django Paginator
- Django Messages - Sending flash messages to the user
- Django Forms - Creating loose forms or based on Models
- Django JSONResponse
- Security in Django
- Tests in Django with Pytest and Unittest
- Mocks for testing in Python
- Introduction to TDD with Django (Test Driven Development)
- Functional tests with Selenium and chromedriver
- Performance and Django Debug Toolbar
- HTML and CSS

## Getting Started

### Clone this repository

```
git clone https://github.com/diogosaucedo/recipes.git
cd recipes
```

### Activate Virtual Environment

```
python -m venv venv

# Windows
venv\Scripts\activate 

# Linux/macOS
source venv/bin/activate 
```

### Instal project dependencies

```
pip install -r requirements.txt
```

### create a .env

Create an `.env` file following the `.env-example` file pattern

### Then simply apply the migrations

```
python manage.py migrate
```

### Create a superuser

```
python manage.py createsuperuser
```

### Run development server

```
python manage.py runserver
```
