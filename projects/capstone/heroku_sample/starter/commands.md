Add dependencies:
```
pip freeze > requirements.txt
```

Migrations:

```
python manage.py db init
python manage.py db migrate
python manage.py db upgrade
```