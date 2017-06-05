# Flask Tutorial

Following Flask tutorial from [Flask website](http://flask.pocoo.org/docs/0.12/tutorial/)

## Virtual Environment

Make virtual environment in root of the project with:
```
python3 -m venv virtual-env
```
Activate it with:
```
source virtual-env/bin/activate
```
Install Requirements with:
```
(virtual-env) ~$ python -m pip install -r requirements.txt
(virtual-env) ~$ python -m pip install --editable .
```

## Database setup
You need to be in **mysite** folder for this command:
```
(virtual-env) ~$ python -m flask initdb
```

## The development web server

You need to be in **mysite** folder for this command:
```
(virtual-env) ~$ python -m flask run
```
