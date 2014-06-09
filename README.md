digital20server
===============

A server system that supports the Digital 20 game and tools framework

Setup
-----

Recommended - virtualenv

  virtualenv .venv\d20

  .venv\d20\Scripts\activate

Install requirements

  pip install -r requirements.txt

Setup database

  python src\manage.py syncdb --noinput
  
Run tests
---------

  python src\manage.py test

Run server
----------

  python src\manage.py runserver
