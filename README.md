# Django REST API sample application

## refs
* [django](http://djangoproject.jp)
* [django-rest-framework](http://www.django-rest-framework.org)

## create process

```sh
python -V # 3.5.3
pip install django djangorestframework
django-admin startproject django_rest_api && cd django_rest_api
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
