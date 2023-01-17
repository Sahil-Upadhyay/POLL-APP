# POLL-APP
My django project. Made a poll app using django.

# Django-Poll-App
Django poll app is a full featured polling app. You have to register in this app to show the polls and to vote. If you already voted you can not vote again. Only the owner of a poll can add poll , edit poll, update poll, delete poll , add choice, update choice, delete choice and end a poll. If a poll is ended it can not be voted. Ended poll only shows user the final result of the poll. There is a search option for polls. Also user can filter polls by name, publish date, and by number of voted.

To migrate the database open terminal in project directory and type:-
python manage.py makemigrations
python manage.py migrate

To use admin panel you need to create superuser using this command:-
python manage.py createsuperuser

To run the program in local server use the following command:-
python manage.py runserver


