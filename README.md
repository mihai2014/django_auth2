# Django Custom User Model

[Tutorial!](https://learndjango.com/tutorials/django-custom-user-model)

## Installation

virtualenv env

source env/bin/activate

pip install -r requirements.txt

(add new fields to user in accounts/models.py)

python manage.py migrate

*(or ./init.sh up to here)*

python manage.py runserver

localhost:8000

Reset password (testing)  will work only if user have an email defined.
Reset mails (testign) will be sent in sent_emails folder.

admin init:

python manage.py createsuperuser

