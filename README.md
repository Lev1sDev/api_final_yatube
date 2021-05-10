# REST API для проекта Yatube

## Стек технологий: Python 3, Django REST Framework, SQlite 3, Simple-JWT.

### реализована аутентификация по JWT-токену.

### Установить зависимости и запустить приложение:
``` git clone https://github.com/Lev1sDev/api_final_yatube.git  ``` \
```python3 -m venv venv``` \
```source venv/bin/activate``` \
```pip3 install -r requirements.txt```


### Выполнить миграции:
```python3 manage.py makemigrations``` \
```python3 manage.py migrate```

### Создать суперпользователя:
```python3 manage.py createsuperuser```

### Привязать статические файлы:
```python3 manage.py collectstatic```

