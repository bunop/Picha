### Hi! Check out the blog post -> [Asynchronous Tasks with Django and Celery](https://realpython.com/blog/python/asynchronous-tasks-with-django-and-celery)

### Run this project inside a docker composed image

Install `docker` and `docker-compose` on your system. Then build and run images
with

```
$ docker-compose up -d
```

Apply migrations in order to initialize database:

```
$ docker-compose run --rm web python manage.py migrate
```

Create a superuser

```
$ docker-compose run --rm web python manage.py createsuperuser
```
