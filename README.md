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

To deploy on AWS:
- `Sign up to AWS Free tier: https://aws.amazon.com/free/`
- `Add Key Pair to AWS EC2 Service`
- `Create EC2 Server Instance`
- `Configure deployment files: setup.sh, supervisor, update.sh & nginx config`
- `Use chmod +x *.sh to make the deployment files executable`
