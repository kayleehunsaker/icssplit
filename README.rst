icssplit
========

.. image:: https://img.shields.io/pypi/v/icssplit.svg
    :target: https://pypi.python.org/pypi/icssplit
    :alt: Latest PyPI version

.. image:: https://travis-ci.org/beorn/icssplit.png
   :target: https://travis-ci.org/beorn/icssplit
   :alt: Latest Travis CI build status

Split big .ics/.ical files into smaller ones for easy import into Google Calendar.

Usage
-----

Installation
------------

Requirements
^^^^^^^^^^^^

Compatibility
-------------

Licence
-------

See Also
--------
 - https://github.com/druths/icssplitter - splits by year - so doesn't work if one year is >1MB
 - https://www.g-transfer.com - doesn't seem to be operational?
 - https://github.com/rtsai/icalutil gcalfiltersplit - lots of dependencies

Authors
-------

`icssplit` was written by `Bjorn Stabell <bjorn@stabell.org>`_.


TODO
----
 - replace Makefile with invoke
 - necessary to have a package?  why not just use a module?  (tox fails)
 - replace docopt with invoke - fix default arg