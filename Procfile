web: gunicorn todo_list.wsgi --log-file -

web: python manage.py migrate && python manage.py collectstatic --no-input && gunicorn todo_list.wsgi