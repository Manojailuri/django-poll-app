# django-poll-app
simple poll app made using django  

## steps to run
### step 1
clone this repository `git clone https://github.com/Manojailuri/django-poll-app.git` <br>
### step 2
`cd change/directory/to/manage.py` <br>
### step 3
change database settings and other settings on pollsite/settings.py
### step 4
run migrations in directory with manage.py in it  
`python manage.py makemigrations polls`
### step 5
run server  
`python manage.py runserver`
### step 6
vist local host server on any browser `http://127.0.0.1:8000/`  
<br>
tests.py in polls directory  
run `python manage.py test polls` for testing
