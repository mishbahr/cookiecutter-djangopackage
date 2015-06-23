=============================
{{ cookiecutter.project_name }}
=============================

.. image:: http://img.shields.io/travis/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}.svg?style=flat-square
    :target: https://travis-ci.org/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}/

.. image:: http://img.shields.io/pypi/v/{{ cookiecutter.repo_name }}.svg?style=flat-square
    :target: https://pypi.python.org/pypi/{{ cookiecutter.repo_name }}/
    :alt: Latest Version

.. image:: http://img.shields.io/pypi/dm/{{ cookiecutter.repo_name }}.svg?style=flat-square
    :target: https://pypi.python.org/pypi/{{ cookiecutter.repo_name }}/
    :alt: Downloads

.. image:: http://img.shields.io/pypi/l/{{ cookiecutter.repo_name }}.svg?style=flat-square
    :target: https://pypi.python.org/pypi/{{ cookiecutter.repo_name }}/
    :alt: License

.. image:: http://img.shields.io/coveralls/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}.svg?style=flat-square
  :target: https://coveralls.io/r/{{ cookiecutter.github_username }}/{{ cookiecutter.repo_name }}?branch=master

{{ cookiecutter.project_short_description}}

Features
--------

* TODO


Quickstart
----------

1. Install ``{{ cookiecutter.project_name }}``::

    pip install {{ cookiecutter.repo_name }}

2. Add ``{{ cookiecutter.app_name}}`` to ``INSTALLED_APPS``::

    INSTALLED_APPS = (
        ...
        '{{ cookiecutter.app_name}}',
        ...
    )

3. Sync database (requires south>=1.0.1 if you are using Django 1.6.x):::

    python manage.py migrate

Documentation
-------------

The full documentation is at https://{{ cookiecutter.repo_name }}.readthedocs.org.
