web: gunicorn gamerzilla.wsgi --limit-request-line 8188 --log-file -
worker: celery worker --app=gamerzilla --loglevel=info
