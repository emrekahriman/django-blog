# Django-Blog
A simple django project

### Live Preview: https://www.emrekhrmnn.cf/ -- <a href="http://example.com/" target="_blank">example</a>
<br>

## Installing

Step by step commands on how to run this project on your computer

1)- Install Virtualenv

```
pip install virtualenv
```

2)- Create Virtualenv

```
virtualenv venv
```

3)- Activate virtual env

```
venv/Scripts/activate
```

4)- Install requirements

```
pip install -r requirements.txt
```
Note: Above lines are required for first time installation

5)- Execute below commands

```
python manage.py makemigrations
python manage.py migrate
```
Note: Above commands should be executed if there is any db level changes

6)- Create superuser for admin access and follow instruction, if not created one

```
python manage.py createsuperuser
```

7)- Collect static files in one location.

```
python manage.py collectstatic
```
<br>

## Running the tests

```
python manage.py runserver
```
And the project is ready for use on your computer!

<br>

## Screenshots of the project

Home Page:

![home](https://user-images.githubusercontent.com/59236526/112477888-7b5faf80-8d84-11eb-87c9-3c37fa112670.jpg)

Posts Page:

![allposts](https://user-images.githubusercontent.com/59236526/112477894-7c90dc80-8d84-11eb-8fd8-5f8d3505a6d5.jpg)

Authors Page:

![authors](https://user-images.githubusercontent.com/59236526/112477900-7dc20980-8d84-11eb-9d2b-d0193387bc51.jpg)

Post Create Page:

![post-create](https://user-images.githubusercontent.com/59236526/112477906-7ef33680-8d84-11eb-9a28-1e61def15dbd.jpg)

Post Update Page:

![update-post](https://user-images.githubusercontent.com/59236526/112477911-80246380-8d84-11eb-9730-7660b4763080.jpg)
