web: gunicorn mysite.wsgi

# Uncomment this `release` process if you are using a database, so that Django's model
# migrations are run as part of app deployment, using Heroku's Release Phase feature:
# https://docs.djangoproject.com/en/4.2/topics/migrations/
# https://devcenter.heroku.com/articles/release-phase

# Descomentar apenas quando for feito o primeiro deploy e o postgres estiver funcionando
release: ./manage.py migrate --no-input
