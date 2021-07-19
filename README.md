# the-library

Books API using Django Rest Framework

## Main commands

### Install venv

```
# In src directory
python3 -m venv venv
```

### Activate venv

```
source venv/bin/activate
```

### Install Django and Django Rest Framework dependencies

```
pip install django djangorestframework
```

### Create the project

```
django-admin startproject library .
```

### Create books app

```
django-admin startapp books
```

### Start server

```
python manage.py runserver
```

### Create migrations

```
python manage.py makemigrations
```

### Run migrations

```
python manage.py migrate
```
