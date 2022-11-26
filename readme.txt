do this.
after activating venv
python manage.py makemigrations
python manage.py makemigrations main
python manage.py migrate

if afther this steps you will have errors with registration comment core/urls.py admin path and settings.py 28 row (#'django.contrib.admin',)
try again 3-5 steps and dont forget to uncomment rows in 7 step.
