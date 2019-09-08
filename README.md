# vinvid
Video Rental application Developed in Python


# djengo Commands 
- django=2.1 [`pipenv install django=2.1`]
- django project setup [`django-admin startproject vinvid`]
- django run server [`python manage.py runserver`] 

# Migration Commands
- Create Database Migrations [`python manage.py makemigrations`]
- Migrate the Chnage to Database [`python manage.py migrate`]
- Making new Migrations [`python manage.py makemigrations`]
- view SQL query for Migration [`python manage.py sqlmigrate movies 0001`]

# Admin App Commands
- Create Super user in admin app [`python manage.py createsuperuser`]


# Deployment
- collect all the static file and copy and paste inside the static folder [`python manage.py collectstatic`]
- server on production [`pipenv install gunicorn`]
- Serve static file on Heroku the package is whilenoise [`pipenv install whiltenoise`]

# Heorku Deployment command
- `heroku login`
- `heroku create`
- `git push heroku master`
- `heroku ps:scale web=1`
- `heroku open`