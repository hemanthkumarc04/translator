step 1: create a repository in git 'translator'
step 2: clone the repository in your local machine
     -git clone <repository_url>
step 3: create a virtual environment
     -py -m venv env
step 4: activate the virtual environment
     -.\env\Scripts\activate
step 5: install django
     -pip install django
step 6: create a django project
     -django-admin startproject translator .
step 7: create a django app
     -python manage.py startapp core
step 8: migrate the database
     -python manage.py migrate
step 9: run the server
     -python manage.py runserver
step 10: 