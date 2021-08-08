# MyExam
RUN PROJECT

python version used - 3.9

django version used - 3.0.5

Pillow

clone the project
```
git clone https://github.com/Jyotirmay02/MyExam.git
```
move to the MyExam directory

run the following command
```
python -m pip install -r requirements.txt
```
run the following commands for migrations
```
python manage.py makemigrations
```

If this error comes ignore it and move on

Migrations for 'auth':
    - Alter field email on user
    
Migrations for 'student':
    - Alter field mobile on student
```
python manage.py migrate
python manage.py makemigrations
```
Now create a superuser/admin
```
python manage.py createsuperuser
```
run the server
```
python manage.py runserver
```
Open following url on your browser
```
http://127.0.0.1:8000/
```



