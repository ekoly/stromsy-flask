# Wordpress Flask

This project is a work in progress. The goal is to create a minimal blog backend in Flask. It uses a wordpress database clone.

### Configuration

The following environment variables should be set:
```
FLASK_APP = "pythonwp"
SECRET_KEY = "XXXXXXXXXXXXXXXXXXXXX"
SQLALCHEMY_DATABASE_URI = "mysql://<username>:<password>@<server>/<dbname>"
```

To configure, it is recommended you set up a virtual environment, then run:

`python setup.py install`

To start the server run:

`flask run`
