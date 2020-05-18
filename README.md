# Project in Django

## how to start project 

1. Go to environment directory e.g. ~/python-tutorial/virtualenvs/trydjango
```
> source bin/activate
```

2. Go back to the directory that contains the project e.g.  ~/python-tutorial/trydjango

3. migrate the database
```
> python manage.py migrate
```

4. start the dev server
```
> python manage.py runserver 8080
```

## Other useful commands

1. create a new app
```
> python manage.py startapp {app-name}
```
