# Bank simple security dashboard

This [Django 3.2](https://docs.djangoproject.com/en/3.2/) project implements a simple dashboard for an imaginary bank. It serves several purposes:
1. show all active access cards (imaginary, of course);
2. track and show the current status of visitors (whether they are in the bank's vault or have left it);
3. show all visit history for a specific visitor.

### How to install

#### Project settings

Create a file called `.env` inside the `project` folder.

Specify the database connection URL (see [DJ-Database-URL documentation](https://github.com/jacobian/dj-database-url#url-schema) for examples of URL formats for various databases):
```commandline
DB_URL=<database URL in specific format>
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
