# Bank simple security dashboard

This Django project implements a simple dashboard for an imaginary bank. It serves several purposes:
1. show all active access cards (imaginary, of course);
2. track and show the current status of visitors (whether they are in the bank's vault or have left it);
3. show all visit history for a specific visitor.

### How to install

Python3 should be already installed. 
Then use `pip` (or `pip3`, if there is a conflict with Python2) to install dependencies:
```commandline
pip install -r requirements.txt
```

### Usage

Execute `main.py` to run the project:

```commandline
python main.py
```

By default, the site will run on [0.0.0.0:8000](http://0.0.0.0:8000) in case you use [repl.it](https://repl.it). Or, if you are running it locally, you'll need to open [127.0.0.1:8000](http://127.0.0.1:8000) in a browser to see it.

### Project Goals

The code is written for educational purposes on online-course for web-developers [dvmn.org](https://dvmn.org/).