command for Win10

# python -m venv venv
 create virtual environment

# ./venv/Scripts/Activate
to activate virtual enviroment

# pip freeze > requirements.txt
to write file with requirements
we need to do it if we add each new requirement

# create file .gitignore and write in the exception of git

# python -m pip install django
install django

# python -m django --version
check in django version

# django-admin startproject mysite
create our new project

# cd mysite
go into directory with our project

# python manage.py runserver
try to start our server
we can find it in browser on adress http://127.0.0.1:8000/ 
or we can create a localserver which would reached from all the PC in local network 
with this command 
# python manage.py runserver 0.0.0.0:8000

we can turn off our server with Ctrl+C (on PC)

# python manage.py startapp polls
create our first app

# python manage.py migrate
create mirgate

#  python manage.py makemigrations polls
make migrations when we've created models

# python manage.py sqlmigrate polls 0001
to check migration's changes

# python manage.py shell
go to the API Django to try create examples of the model

# python manage.py createsuperuser
create superuser