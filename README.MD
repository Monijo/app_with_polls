# Application with polls
1. python manage.py startapp polls
2. view->urls.py->settings.urls(include)
3. First migration->create tables from settings/INSTALLED_APPS
4. 4.create models, add app to install aps 'polls.apps.PollsConfig'
5. migracje w sql : $ python manage.py sqlmigrate polls 0001
6. checking problems :  py manage.py check

