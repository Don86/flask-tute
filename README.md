# Basic CRUD App in Flask

ref: https://www.youtube.com/watch?v=Z1RJmh_OqeA

## Setup

```
# from scratch

# install virtualenv
pip3 install virtualenv

# create and start virtual env
virtualenv env
source env/bin/activate

pip3 install flask flask-sqlalchemy
```

## Init

```
touch app.py
```

## Pushing to Heroku

DL and install `Heroku CLI`.

Freeze requirements (produces `requirements.txt` file)
```
pip3 install gunicorn
pip3 freeze > requirements.txt
```


### Notes

This is an *extremely* simplistic example. To quote [hackersandslackers](https://hackersandslackers.com/flask-application-factory):

>Are you the type of person to start an app by first creating an `app.py` file in our base directory? If so, please stop - this simply isn't a realistic way to build production-ready applications.

Flask convention is the *application factory* pattern. 
