
# Project setup 
```
virtualenv venv_linux
source venv_linux/bin/activate
pip install Django==1.11.8
mkdir src && cd src
django-admin startproject ecommerce .       # Create django project
```

# Django command
```
python manage.py runserver                  # Run web server
python manage.py migrate                    # Migrate database
python manage.py createsuperuser            # Create superuser
```

# Reference
- https://www.djangoproject.com/download/
- https://getbootstrap.com/docs/4.0/getting-started/introduction/#starter-template
- https://docs.djangoproject.com/en/2.0/ref/forms/widgets/
- https://docs.djangoproject.com/en/2.0/topics/auth/default/#how-to-log-a-user-in
