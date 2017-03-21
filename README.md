# Django REST API sample application

## refs
* [django](http://djangoproject.jp)
* [django-rest-framework](http://www.django-rest-framework.org)
* [Django REST Frameworkを使って爆速でAPIを実装する](http://qiita.com/kimihiro_n/items/86e0a9e619720e57ecd8)

## create process

```sh
python -V # 3.5.3
pip install django djangorestframework
django-admin startproject django_rest_api && cd django_rest_api
python manage.py migrate
python manage.py createsuperuser

python manage.py startapp blog
python manage.py makemigrations
python manage.py migrate

python manage.py runserver
```
