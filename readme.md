# Django Mysql

## 1. MySQL install

```sudo
pip install pymysql
pip install mysqlclient
```

## 2. settings.py

```python
DATABASES = {
    'default': {
        'ENGINE': 'django.db.backends.mysql',
        'NAME': 'django_mysql',
        'USER': 'root',
        'PASSWORD': '',
        'HOST': 'localhost',
        'PORT': '3306',
    }
}
```

## 3. Migrate

```sudo
python manage.py migrate
```
