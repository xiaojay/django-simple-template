.. {% comment %}

===============
Django Simple Template
===============

To use ``django-layout`` run the following command::

     django-admin.py startproject --template=http://github.com/xiaojay/django-simple-template/zipball/master --extension=py,rst,gitignore project_name

.. note:: The text following this comment block will become the README.rst of the new project.

-----

.. {% endcomment %}

{{ project_name }}
======================

Quickstart
----------

To bootstrap the project::

    mkvirtualenv {{ project_name }}
    workon {{ project_name }}
    cd path/to/{{ project_name }}/repository
    pip install -r requirements.pip
    manage.py syncdb --migrate

