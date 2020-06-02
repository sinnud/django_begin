# django_begin


Learn online book

A complete beginner's guide to django

URL: https://simpleisbetterthancomplex.com/series/beginners-guide/1.11/

Start this learn from 20200601

logs below:

20200601: superuser admin with password Jeffery45!@

20200601: Refer to https://stackoverflow.com/questions/43139081/importerror-no-module-named-django-core-urlresolvers
          The code : from django.core.urlresolvers import reverse
          should be changed to : from django.urls import reverse
          in myproject/boards/tests.py

20200601: Refer to https://www.valentinog.com/blog/python-recipes/
          The models.ForeignKey function need argument "on_delete=models.PROTECT"
          Hope this change will not affect the later testing

20200601: use command 

          python -m venv venv

          instead of command in online doc: virtualenv venv -p python3.6

20200601: create folder django_begin on 192.168.1.213 machine