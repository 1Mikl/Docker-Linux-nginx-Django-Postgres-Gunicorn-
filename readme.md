# Запуск

```
docker run -p 8000:8000 -p 80:80 -p 5432:5432 burevol/django-work:latest
```

Gunicorn доступе на порту 8000, Nginx на порту 80, Postgres на порту 5432
