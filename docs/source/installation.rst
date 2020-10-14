Installation
============

Pip
---

Use the Python package manager `pip <https://pypi.org/project/pip/>`__ to install the package and dependencies.

.. code-block:: bash
   
   pip install caribbean-outbreak-tracker


GitHub Repo
-----------

Clone the repo and navigate to the working directory.

.. code-block:: bash
   
   git clone https://github.com/obikag/caribbean-outbreak-tracker.git
   cd caribbean-outbreak-tracker

Using `setuptools <https://pypi.org/project/setuptools/>`__ install the package and dependencies.

.. code-block:: bash
   
   python setup.py install


Admin Usage
-----------

Create a `Django <https://www.djangoproject.com/>`__ project and navigate to working directory.

.. code-block:: bash
   
   django-admin startproject example-site
   cd example-site

Add the outbreak tracker app to you settings.py file

.. code-block:: python
   
   INSTALLED_APPS = [
       ...,
       'outbreak_tracker',
   ]

Make migrations and migrate changes to the database

.. code-block:: bash
   
   python manage.py makemigrations
   python manage.py migrate


Navigate to the project's admin site to access the models and enter the relevant information.