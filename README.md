# 1. Installing Virtual Environment - Isolating each project setup

python -m venv <envname>

e.g: ` python -m venv myenv `

# 2. Activating Virtual Environment

myenv\scripts\activate

# 3. Install Django

pip install django

# 4. Creating project

django-admin startproject <projname>

django-admin startproject jobportal

## Creating app

django-admin startapp jobportal

(register app in settings.py)

## Make migrations - converting models to database

python manage.py makemigrations

python manage.py migrate

# 5. Running Project

python manage.py runserver

## Creating admin user

python manage.py createsuperuser
