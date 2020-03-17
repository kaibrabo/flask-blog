## Quickstart

`$ mkdir myproject`
`$ cd myproject`
`$ python3 -m venv venv`

### Activate the environment

`$ . venv/bin/activate`

### Install Flask

`$ pip install Flask`

From the myproject directory:

`$ export FLASK_APP=flaskr`
`$ export FLASK_ENV=development`
`$ flask run`

### Initialize the database

`$ export FLASK_APP=flaskr`
`$ flask init-db`
`$ flask run`

### Tooling

Formatter - 'Black'