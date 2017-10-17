
How to run project
---------------

### Prerequirements

* python3 (latest version)
* virtual environment (see at the bottom how to install it);
* packages (after you've created virtual env, activate it and install them using `pip install -r requirements.txt` in words folder):
  * django;
  * djangorestframework
  * django-cors-headers;
  * requests

### How to create a virtual env for python3

python3 -m venv /path/to/new/virtual/environment

### How to migrate db at the first time

python words/manage.py migrate

### How to run server

python words/manage.py runserver

### How to run tests

words/manage.py test cards.tests
