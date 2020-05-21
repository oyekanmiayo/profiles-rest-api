# Profiles REST API

A project to help me understand the Django & Django REST Framework by example.

Requirements:
- Vagrant
- Virtual Box
- Django
- Django Rest Framework

To Run:
- `vagrant up`
- `vagrant ssh`
- `cd /vagrant`
- `source ~/env/bin/activate`
- `python manage.py runserver 0.0.0.0:8000`

To create or update migrations:
- `python manage.py makemigrations`

To apply migrations to the database:
- `python manage.py migrate`
