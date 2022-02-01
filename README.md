# Introduction to tests

Vou documentar melhor esse exemplo. I will, soon

## Install Requirements

$ pip install -r requirements.txt

## RUN Flask Application

$ export FLASK_APP=app.py  
$ flask run

## RUN Tests

$ py.test

## RUN Coverage

$ coverage run --source=app -m py.test  
$ coverage report -m   
$ coverage html
