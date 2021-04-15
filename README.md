# DRF Backend API
> Django Rest framework backend API server.

## Setup

The following steps will walk you thru installation on a Mac. Linux should be similar.
It's also possible to develop on a Windows machine, but I have not documented the steps.
If you've developed Django apps on Windows, you should have little problem getting
up and running.

### Dependancies

- Python 3.8.9 
- PostgreSQL 13.2
- Django 3.2

Then you will go to config folder and rename `db_config.sample` to `db_config.py`

Create virtualenv in your system then follow the commends:
```` virtualenv venv --python=python3.8 ````

If you successfully create the virtualenv then activate:
```source venv/bin/activate```


After that you may run `requirements.txt` file following the command:
```angular2html
pip install -r requirements.txt
./manage.py migrate
./manage.py runserver
```
