# music_controller

# 01 Setup

py -3 -m venv venv 

venv\Scripts\activate

pip install django djangorestframework

django-admin startproject music_controller

django-admin startapp api

python .\manage.py makemigrations

python .\manage.py migrate

python .\manage.py runserver