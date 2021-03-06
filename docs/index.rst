.. include:: ../README.rst

Differences to Django's staticfiles contrib app
-----------------------------------------------

Features of ``django-staticfiles`` which Django's ``staticfiles`` **doesn't**
support:

* ``STATICFILES_EXCLUDED_APPS`` settings -- A sequence of dotted app paths
  that should be ignored when searching for static files

* Legacy 'media' dir file finder -- a staticfiles finder that supports the
  location for static files that a lot of 3rd party apps support
  (``staticfiles.finders.LegacyAppDirectoriesFinder``).

See the :doc:`settings` docs for more information.

Contents
--------

.. toctree::
   :maxdepth: 2

   commands
   helpers
   settings
   changelog
