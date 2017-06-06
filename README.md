# django-requests-tracker

Tracking http requests send by [python-requests](https://github.com/kennethreitz/requests) inside a [Django](https://www.djangoproject.com) application.

## Installation

To install using `pip`:

    pip install django-requests-tracker

To install using `easy_install`:

    easy_install django-requests-tracker

## Configuration

1. Put `requests_tracker` into your `INSTALLED_APPS`:

    INSTALLED_APPS = [
        ...
        'requests_tracker',
    ]

2. Create `requests_tracker` database tables by running:

    python manage.py migrate
