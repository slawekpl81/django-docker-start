# django-docker-start
Django project boilerplate

Django project boilerplate with docker-compose
DB: postgresql

start app:
docker-compose up --build -d

create superuser:
docker-compose exec app python manage.py createsuperuser
