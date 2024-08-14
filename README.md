# ys-django-backend

## docker build
> docker build .
> docker compose build

## django setting
> docker compose run --rm app sh -c "django-admin startproject app ."

## create admin user 
> docker compose run --rm app sh -c "python manage.py migrate"
> docker compose run --rm app sh -c "python manage.py createsuperuser"

