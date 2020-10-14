Models
======

Introduction
------------

The outbreak tracker consists of five (5) models. They are as follows:

* **Disease** - Stores information about the pandemic disease
* **Demographics** - Stores country information such as name, location and population size
* **TrackerLog** - Stores disease infection and death statistics from source.
* **FAQSection** - Stores section topics for a FAQ page
* **FAQDetail** - Stores question/answer details for each FAQ section

Each of these models are used to build the tracker and can be accessed within the Django project.

Accessing Models
----------------

To access the outbreak tracker models within your code, you can use Python's ``import`` statement

.. code-block:: python
   
   # To import all models
   import oubreak_tracker.models

   # To import a specific models e.g. TrackerLog
   from outbreak_tracker.models import TrackerLog

Fields and Functions
--------------------------

Coming Soon