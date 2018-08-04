# Flask Tutorial with SQLite3

The tutorial is available from the following link: http://flask.pocoo.org/docs/1.0/tutorial/

## Install the project
```
pip install -e .
```

## Initialize the SQLite 3 Database
```
flask init-db
```

## Run the project
```
export FLASK_APP=flaskr
export FLASK_ENV=development
flask run
```

## Test the project
To able to run the test, first install the pytest package

```
pip install pytest
```

The first command is the default configuration, the second is to show the method name instead of dots. 
```
pytest
pytest -v
```

### Checking project test coverage
First install the package
```
pip install coverage
```

Now we check the project with this command:
```
coverage run -m pytest
coverage report
```