## createsuperuser 가 안될 때
* [stack overflow](http://stackoverflow.com/questions/14059573/cant-create-super-user-django)

```
python manage.py syncdb --noinput
python manage.py migrate
python manage.py createsuperuser
```

## virtualenv 주의점
* PATH 관련 : 특히 DB 관련 path 주의할 것.
