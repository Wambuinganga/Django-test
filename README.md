Pezesha Project 

This project is build using Django framework for python
The admin is in charge of registering products and can delete both the products and users.
The user can register, login, update their details as well as view and order products

Errors
Page not found error(error 404) when the route redirect fails

Credentials 
To login, the admin is required to login with the following details
Username:pezeshaintern
email:wambuinganga07@gmail.com
password:intern

##Features
An admin dashboard that allows the admin to have full control of the functionalities(add, delete and update)
A user interface where the user can register, login and update their details
 
##Installation
Commands used and their functionality in the project
mkdir My-project to create a folder in my desktop
$python -m venv envone to create a virtual environment
$pip install django to install django framework in my project
$python manage.py startproject pezesha  creates a project
$cd pezesha 
$python manage.py startapp user to create an app inside my project
$python manage.py shell to activate the shell
>>from django.db.models import fields_all to import all fields
>>fields all to confirm the fields imported
$python manage.py makemigrations  and migrate to make database migrations
$python .py  createsuperuser. It will prompt you to enter name, email and password for the superuser to be created
$python manage.py runserver activates the server and gives you the url for the server. 
##Pushing to github
Created a new repository in github
In the command line
$git init
$git status 
$git add . to add all files
$git  commit -m"enter your message here"
$git remote add origin master
$git push -u origin master
##Framework
Django framework for python

##Contributions
Fork (https://github.com/Wambuinganga/Django-test.git)
