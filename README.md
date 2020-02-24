# glitch-flask-starter
A starter project for python web development in [glitch](https://glitch.com/).  

## Requirements 

* python3
* [flask](https://flask.palletsprojects.com/en/1.1.x/) 

## Running locally

* Install pipenv: `python3 -m pip install pipenv`
* Install dependencies: `pipenv install --ignore-pipfile`
* Run: `pipenv run python server.py`

## Adding new dependencies

* Install development dependencies: `pipenv install --dev`
* Enter environment: `pipenv shell`
* Install the new dependency: `pip install <package>`
* View dependencies: `pip list`
* Generate new lockfile: `pipenv lock`
* Update requirements.txt for glitch, since it only has pip: 
  * `python -m pip freeze > requirements.txt`

## Issues

* I haven't figured out how to use pipenv with glitch.

## Credits

Adapted from [flask-python3](https://glitch.com/edit/#!/flask-python3).
