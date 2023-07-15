## Commands used

For Django libraries in local setup
```
pip install -r requirements.txt
```

To create a django project
```
django-admin startproject basics
```

To test django application running
```
./manage.py runserver
```

To start docker containers, we use docker-compose
```
docker-compose up -d
```

To stop docker containers
```
docker-compose down
```

Important informations

- Dockerfile ports **{local-por}:{container-port}**
- Use docker volumes for postgres due to permission issues for local mapping