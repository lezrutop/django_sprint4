* cd ~/Desktop/django_sprint4
* python -m venv venv
* source venv/Scripts/activate
* pip install -r requirements.txt
* cd blogicum/blogicum
* python manage.py migrate
* python manage.py loaddata ../../db.json
* python manage.py createsuperuser
* python manage.py runserver

* http://127.0.0.1:8000/
