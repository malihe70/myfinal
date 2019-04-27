# myfinal

1-what is this app used for?
It uses for polls-app ,add admin , add user , add question ,choice ,and edit  . . .

2-what does one need to install before running the app ,what are the requirements?
python
django
visual studio code

3-How to install all the Python packages from the requirements.txt (we know that at least one is listed in there)? 
py manage.py -r reqirements.txt

4- How to run the app locally? 
py manage.py runserver

5- Which are some relevant URLs for the app? Eg. how to access the admin interface? 
172.0.0.1.8000/admin

6- A simple example of the app’s functionality. Eg. how to add a new Polls and Questions? How can I submit an answer to a question? 

polls/admin.py

from django.contrib import admin

from .models import Question

admin.site.register(Question)
for polls we can run this:
py manage.py makemigrations polls

username:admin19
pass:pm2281071332
