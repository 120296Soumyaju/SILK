# SILK

Mini Project to develop ToDo App using Django 

Todo-App
Todo app using  python, django , django orm

MyDoList

It is app that you can create a user specific to-do list and item.

You can give a name, description, deadline, and status to any item. 

You can filter to-do items (status complete or not, expired, name) on a to-do list. 
To-item ordered by name.


Requirements

django https://www.djangoproject.com/download/
python version 3.6 or above https://www.python.org/downloads/
DB Browser for SQLite https://sqlitebrowser.org/dl/
PYCHARM IDE COMMUNITY VERSION  : https://www.jetbrains.com/pycharm/download/#section=windows


Understanding Todo List Project:

In the code is a Django project called todolist that contains a single app called todo.
You can open up todo/urls.py, where the URL configuration for this app is defined.
Open up todo/views.py, where all the logic for this app is defined.
Open up todo/models.py, there is three class in models.py, User model inherits from Abstract user. 
Dolist models have many to one and many to many relationship with User and Item model.

INSTRUCTIONS TO RUN TODO APP

Clone the repo : https://github.com/120296Soumyaju/SILK.git to your System using git bash and open folder using PYCHARM IDE

In your terminal, cd into the todolist.
Run python manage.py makemigrations todo to make migrations for the todo app.
Run python manage.py migrate to apply migrations to your database.
Run python manage.py runserver and open the http://127.0.0.1:8000/ in your browser.


