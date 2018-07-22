reference to [https://docs.docker.com/compose/django/](https://docs.docker.com/compose/django/)

with some tips:

run in daemon

```shell
docker-compose up -d
```

init project.

```shell
docker-compose run web django-admin.py startproject composeexample .
```

check logs

```shell
docker-compose logs -f
```

interact with web container

```shell
docker-compose run web bash
```


