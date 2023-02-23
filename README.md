# Code Snippets API

Code Snippets API is a pastebin code highlighting Web API that allows users to add favorite code snippets. It is built with Django/Django REST Framework, and uses the pygments code highlighting library.

## Clone the Repository

```
git clone https://github.com/becathey/code-snippets-django
```

## Create & Activate a Virtual Environment

In the project directory, create and activate a virtual environment. For example:

```
python3 -m venv .venv
source .venv/bin/activate
```

## Install the Dependencies

To install the dependencies, run:

```
pip install -r requirements.txt
```

## Run the App

To run the app in development mode, run:

```
python manage.py runserver
```

Open [http://localhost:8000](http://localhost:8000) in the browser to view the application.

## Deploy the App

To learn how to make the application production-ready and to deploy it, see the Django documentation:

[How to Deploy Django](https://docs.djangoproject.com/en/4.1/howto/deployment/)