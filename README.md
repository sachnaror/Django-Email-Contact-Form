
Django Email/Contact Form
=========================


A simple contact form that sends email for a Django 5.0. We can take advantage of Django's built-in [email support](https://docs.djangoproject.com/en/dev/topics/email/) to make this relatively painless and then send the emails for real using the SendGrid email service.

[Initial setup](#initial-setup)
-------------------------------


$ python3 \-m venv .venv

$ source .venv/bin/activate

(.venv) $ pip3 install django



**Next let's create a new Django project called `config` and within it an app called `sendemail`**

(.venv) $ django-admin startproject config

(.venv) $ python manage.py startapp sendemail



**To make sure everything installed correctly let's `migrate` and then `runserver`**

(.venv) $ python manage.py migrate

(.venv) $ python manage.py runserver


**If you open you browser to [127.0.0.1:8000](http://127.0.0.1:8000/) you should see the default django launch screen we all are familiar with. Happy coding!
**
