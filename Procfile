release: python manage.py makemigrations --no-input
release: python manage.py migrate --no-input
web: gunicorn project2_app.wsgi
web: python project2_app/manage.py runserver 0.0.0.0:$PORT