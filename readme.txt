do this.
after creating venv
python manage.py makemigrations
python manage.py makemigrations main
python manage.py migrate

if afther this steps you will have errors comment core/urls.py admin path and settings.py 28 row (#'django.contrib.admin',)