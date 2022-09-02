# pythonanywhere
path that contains manage.py
/home/zenithciw/funs/budgetanalytics 
path that contains settings.py
/home/zenithciw/funs/budgetanalytics/budgetanalytics

/home/zenithciw/.virtualenvs/mysite-virtualenvs

CSS not work follow the following steps

STATIC_URL = '/static/'

STATIC_ROOT=os.path.join(BASE_DIR,'static')

MEDIA_ROOT=os.path.join(BASE_DIR,'media')

MEDIA_URL='/media/'
2-collect static files using bash console

python manage.py collectstatic
