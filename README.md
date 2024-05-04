# TO-DO-LIST
TO RUN THE FOLLOWING PROJECT FOLLOW THIS STEPS.

-CREATE VIRTUAL ENVIRONMENT
  >python -m venv env_site

-ACTIVATE VIRTUAL ENVIRONMENT
  >.\env_site\Scripts\activate.ps1

-Install Django
  >pip install django

-START A PROJECT WITH THE FOLLOWING
>django-admin startproject todo_site

-CHANGE THE DIRECTORY TO 
>cd todo_site

-CREATE AN APP
>py manage.py startapp todo

-MIGRATION OF FILE TO DATABASE
>python manage.py makemigrations
>python manage.py migrate

-RUNSERVER
python manage.py runserver
