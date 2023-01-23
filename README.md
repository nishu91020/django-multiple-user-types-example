# Django School

[![Python Version](https://img.shields.io/badge/python-3.6-brightgreen.svg)](https://python.org)
[![Django Version](https://img.shields.io/badge/django-2.0-brightgreen.svg)](https://djangoproject.com)

This is an example project to illustrate an implementation of multiple user types. In this Django app, teachers can create quizzes and students can sign up and take quizzes related to their interests.

## Running the Project Locally

First, clone the repository to your local machine:

```bash
git clone https://github.com/sibtc/django-multiple-user-types-example.git
cd django-multiple-user-types-example
```

### Create a virtual environment

First install [Pipenv](https://pipenv.pypa.io/en/latest/), if you don't have it.

```bash
python3 -m pip install pipenv
```

then activate the virtual env shell

```bash
python3 -m pipenv shell
```

It will activate the virtual environment in the terminal

### Install the requirements

```bash
pip install -r requirements.txt
```

### Create the database

```bash
python manage.py migrate
```

### Finally, run the development server

```bash
python manage.py runserver
```

The project will be available at **127.0.0.1:8000**.

## License

The source code is released under the [MIT License](https://github.com/sibtc/django-multiple-user-types-example/blob/master/LICENSE).
