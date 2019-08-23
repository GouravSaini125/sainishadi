web: gunicorn sainishadi.wsgi --log-file -
web: python manage.py collectstatic --no-input; gunicorn sainishadi.wsgi --log-file - --log-level debug