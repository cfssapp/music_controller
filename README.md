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

# 02 Django REST Framework

python .\manage.py makemigrations

python .\manage.py migrate

serializers.py

# 03 React Webpack Babel

cd .\music_controller\
npm

django-admin startapp frontend
cd .\frontend\

npm init -y

npm i webpack webpack-cli --save-dev

npm i @babel/core babel-loader @babel/preset-env @babel/preset-react --save-dev

npm i react react-dom --save-dev

npm install @material-ui/core

npm install @babel/plugin-proposal-class-properties

npm install react-router-dom

npm install @material-ui/icons

npm run dev

python .\manage.py runserver