# M2T1 - Webapp #1

## goals
- to learn basic flask prrgramming
- to be able to repeat a server config
- maybe to fave fun

# lessons learned

## instructions
intitial tutorial: http://blog.pythonanywhere.com/121/
but we're using codespaces instead of PA

install library:

first setup up virtualenviroment
- pip install virtualenv
- virtualenv venv
- source venv/bin/activate
now we have our "venv" enviroment, so we can install things in it.
to turn it off:
- deactivate

start installing requirments:
 - pip install flask
 - pip freeze > requirements.txt

 now we can weite our minimal Flask app to test it
 TODO: write a Flask app that does somthing usefull

 to start
 - flask --app hello run

export FLASK_APP=xxx.py
flask run