## start the workers
```
celery --app api.tasks worker --loglevel=info -P solo
```
## this didn't
```
celery -A tasks worker --loglevel=INFO
```
## start the django server
```
python manage.py runserver
```
