# django-crud

# Development

create an environment on anaconda with python 3.12.2
  1. `conda create -p py_env python==3.12.2`
  2. `conda activate py_env/`
  3. `pip install -r requirements.txt`

### Conda commands

1. list envs
`conda info --envs`

2. activate the env
`conda activate envname`

## Create a django app
Navigate to `core` directory and run `python manage.py startapp home`

## Start development server
Navigate to `crm` directory and run `python manage.py runserver`.
Application will run on http://localhost:8000/

## Migrate all default database files to all the installed apps
`python manage.py migrate`

## Create super user on the database