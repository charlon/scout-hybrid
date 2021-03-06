# scout-flask
Flask rewrite of Scout - which uses Turbolinks to handle the HTML content.

### Prerequisites
* Python
* Virtualenv

### Installation

Clone this repository:
```
  $ git clone https://github.com/charlon/scout-flask.git
  $ cd scout-flask
```
Create/start Virtualenv:
```
  $ virtualenv .
  $ source bin/activate
```

Install Flask and dependencies
```
  $ pip install -r requirements.txt
```

Run the Flask application
```
  $ export FLASK_APP=run.py
  $ flask run
```

View the application in a browser:
```
  http://127.0.0.1:5000/
```
