#Api-flask

###Step 1:
Make a file called Pipfile
  
###Step 2:
Activate virtualenv with pipenv

  $pipenv shell
  
###Step 3:
  With virtualenv activated install the next libraries.
  $pipenv install flask flask-cors flask-migrate flask-sqlalchemy
  flask-jwt-extended flask-scripts flask-bcrypt flask-mail
  
The documentation of libraries:
- flask - http://palletsprojects.com/p/flask/
- flask-cors - http://flask-cors.corydolphin.com/en/latest/api.html#extension
- flask-migrate- http://flask-migrate.readthedocs.io/en/latest
- flask-sqlalchemy - http://flask-sqlalchemy.palletprojects.com/en/2.x
- flask-jwt-extended - http://flask-jwt-extended.readthedocs.io/en/stable/
- flask-script - http://flask-script.readthedocs.io/en/latest/
- flask-bcrypt - http://flask-bcrypt.readthedocs.io/en/latest/
- flask-mail - http://pythonhosted.org/Flask-Mail/
  
###Step 4:
Make a new file called manage.py as main app.
  
###Step 5:
Write inside the manage.py the next code: 
  
  from flask import
