django-crash-starter
====================

[![Build Status](https://travis-ci.com/roygreenfeld/django-crash-starter.svg?branch=master)](https://travis-ci.com/roygreenfeld/django-crash-starter)



Powered by [Cookiecutter](https://github.com/cookiecutter/cookiecutter), django-crash-starter is the project template
for the [Django Crash Course tutorial book](https://www.roygreenfeld.com/products/django-crash-course) by Daniel and Audrey Roy-Greenfeld.

Features
--------

-   For Django 3+
-   Works with Python 3.8+
-   Renders Django projects with 100% starting test coverage
-   Twitter [Bootstrap](https://github.com/twbs/bootstrap) v4
-   [12-Factor](http://12factor.net/) based settings via
    [django-environ](https://github.com/joke2k/django-environ)
-   Secure by default. We believe in SSL.
-   Optimized development and production settings
-   Registration via
    [django-allauth](https://github.com/pennersr/django-allauth)
-   Comes with custom user model ready to go
-   Media storage using whitenoise
-   Run tests with unittest or pytest
-   PostgreSQL SQLite3
-   Default integration with
    [pre-commit](https://github.com/pre-commit/pre-commit) for
    identifying simple issues before submission to code review

Constraints
-----------

- Very small scope. New feature pull requests will generally be rejected.
- Only maintained 3rd party libraries are used.
- Environment variables for configuration
