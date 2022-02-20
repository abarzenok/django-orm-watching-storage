# Bank simple security dashboard

This [Django 3.2](https://docs.djangoproject.com/en/3.2/) project implements a simple dashboard for an imaginary bank. It serves several purposes:
1. show all active access cards (imaginary, of course);
2. track and show the current status of visitors (whether they are in the bank's vault or have left it);
3. show all visit history for a specific visitor.

### How to install

#### Project settings

Create a file called `.env` inside the `project` folder.

Specify the database connection properties (for a detailed description of Django database settings, see the official [Django databases documentation](https://docs.djangoproject.com/en/3.2/ref/databases/)):
```commandline
DB_ENGINE=<database engine (see documentation)>
DB_HOST=<database hostname or IP address>
DB_PORT=<database port. By default, it's 5432 for PostgreSQL, 3306 for MySQL, etc.>
DB_NAME=<name of the database you want to connect>
DB_USER=<database user with required rights>
DB_PASSWORD=<user password>
```

You can also define the `DEBUG` mode (`False` by default)::
```commandline
DEBUG=True
```

#### Installing dependencies
Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```commandline
pip install -r requirements.txt
```

### Usage

Execute the following to run the project:

```commandline
python manage.py runserver 0.0.0.0:8000
```

You'll need to open [127.0.0.1:8000](http://127.0.0.1:8000) in a browser to see it. Also, see [Django runserver documentation](https://docs.djangoproject.com/en/3.2/ref/django-admin/#runserver).

### Project Goals

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).
