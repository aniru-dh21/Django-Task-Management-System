# Task Management System Using Django

Django is a very robust full-stack web framework. It uses Python on the server side 
and provides API to integrate with almost any front-end web frameworks like React, Next, Vue, and Angular. 
In Django developers use MVT(Model View Template) architecture to build an application. In this
project on **Task Management System Using Django**, we are going to stick with built-in Django templates
that use the [Django Template Langauge](https://docs.djangoproject.com/en/5.0/ref/templates/language/). This 
project is a complete demonstration of Task Management System where the user can create their account and log in 
to the application. In the tasks section user can create a task with the rich text editor. 
From the home page, the user is capable of viewing, editing, and deletion a particular task.

## Overview

1. [Python](https://www.python.org/)
2. [Django Web Framework](https://www.djangoproject.com/)
3. [Sqlite](https://www.sqlite.org/index.html)
4. [Bootstrap](https://getbootstrap.com/)
5. HTML, CSS and JavaScript

## Building Django Task Management System

This project will have limited functionalities of a regular task management system software or application. The user can create an account and login to the application with proper form validation of each field. After Login, the user will be automatically redirected to the home or all tasks section of the application containing four columns To Do, Started, Complete, and Archive. Initially, tasks will be empty and the user can add new tasks with the task details. The project also includes a strict authentication system as all the routes are protected thus unauthorized users cannot access any page and will be automatically been redirected to the login page.

## Steps to implement the Project

1. Clone this repository to the local machine:
```bash
git clone https://github.com/aniru-dh21/Django-Task-Management-System.git
```

2. Install the Python Dependencies:
```bash
pip install -r requirements.txt
```

3. Execute the following command:
```bash
python manage.py makemigrations
```
This is to create a package of all the changes we made in the models.py file of the **base** application

4. Execute the following command:
```bash
python manage.py migrate
```
This is to apply all the changes to the database schema.

5. Execute the following command:
```bash
python manage.py runserver
```
This is to start the local development server of Django to view the application we created
