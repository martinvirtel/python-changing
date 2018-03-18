========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor| |requires|
        | |coveralls| |codecov|
    * - package
      - | |version| |wheel| |supported-versions| |supported-implementations|
        | |commits-since|

.. |docs| image:: https://readthedocs.org/projects/python-changing/badge/?style=flat
    :target: https://readthedocs.org/projects/python-changing
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/martinvirtel/python-changing.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/martinvirtel/python-changing

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/martinvirtel/python-changing?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/martinvirtel/python-changing

.. |requires| image:: https://requires.io/github/martinvirtel/python-changing/requirements.svg?branch=master
    :alt: Requirements Status
    :target: https://requires.io/github/martinvirtel/python-changing/requirements/?branch=master

.. |coveralls| image:: https://coveralls.io/repos/martinvirtel/python-changing/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/martinvirtel/python-changing

.. |codecov| image:: https://codecov.io/github/martinvirtel/python-changing/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/martinvirtel/python-changing

.. |version| image:: https://img.shields.io/pypi/v/changing.svg
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/changing

.. |commits-since| image:: https://img.shields.io/github/commits-since/martinvirtel/python-changing/v0.1.0.svg
    :alt: Commits since latest release
    :target: https://github.com/martinvirtel/python-changing/compare/v0.1.0...master

.. |wheel| image:: https://img.shields.io/pypi/wheel/changing.svg
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/changing

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/changing.svg
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/changing

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/changing.svg
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/changing


.. end-badges

Detect Changes in a JSON object stream

* Free software: Apache Software License 2.0

Installation
============

::

    pip install changing

Documentation
=============

https://python-changing.readthedocs.io/

Development
===========

To run the all tests run::

    tox

Note, to combine the coverage data from all the tox environments run:

.. list-table::
    :widths: 10 90
    :stub-columns: 1

    - - Windows
      - ::

            set PYTEST_ADDOPTS=--cov-append
            tox

    - - Other
      - ::

            PYTEST_ADDOPTS=--cov-append tox
