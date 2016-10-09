========
Overview
========

.. start-badges

.. list-table::
    :stub-columns: 1

    * - docs
      - |docs|
    * - tests
      - | |travis| |appveyor|
        | |coveralls| |codecov|
        | |codacy|
    * - package
      - |version| |downloads| |wheel| |supported-versions| |supported-implementations|

.. |docs| image:: https://readthedocs.org/projects/aws-ipyparallel-cluster/badge/?style=flat
    :target: https://readthedocs.org/projects/aws-ipyparallel-cluster
    :alt: Documentation Status

.. |travis| image:: https://travis-ci.org/midnighter/aws-ipyparallel-cluster.svg?branch=master
    :alt: Travis-CI Build Status
    :target: https://travis-ci.org/midnighter/aws-ipyparallel-cluster

.. |appveyor| image:: https://ci.appveyor.com/api/projects/status/github/midnighter/aws-ipyparallel-cluster?branch=master&svg=true
    :alt: AppVeyor Build Status
    :target: https://ci.appveyor.com/project/midnighter/aws-ipyparallel-cluster

.. |coveralls| image:: https://coveralls.io/repos/midnighter/aws-ipyparallel-cluster/badge.svg?branch=master&service=github
    :alt: Coverage Status
    :target: https://coveralls.io/r/midnighter/aws-ipyparallel-cluster

.. |codecov| image:: https://codecov.io/github/midnighter/aws-ipyparallel-cluster/coverage.svg?branch=master
    :alt: Coverage Status
    :target: https://codecov.io/github/midnighter/aws-ipyparallel-cluster

.. |codacy| image:: https://img.shields.io/codacy/REPLACE_WITH_PROJECT_ID.svg?style=flat
    :target: https://www.codacy.com/app/midnighter/aws-ipyparallel-cluster
    :alt: Codacy Code Quality Status

.. |version| image:: https://img.shields.io/pypi/v/aws-cluster.svg?style=flat
    :alt: PyPI Package latest release
    :target: https://pypi.python.org/pypi/aws-cluster

.. |downloads| image:: https://img.shields.io/pypi/dm/aws-cluster.svg?style=flat
    :alt: PyPI Package monthly downloads
    :target: https://pypi.python.org/pypi/aws-cluster

.. |wheel| image:: https://img.shields.io/pypi/wheel/aws-cluster.svg?style=flat
    :alt: PyPI Wheel
    :target: https://pypi.python.org/pypi/aws-cluster

.. |supported-versions| image:: https://img.shields.io/pypi/pyversions/aws-cluster.svg?style=flat
    :alt: Supported versions
    :target: https://pypi.python.org/pypi/aws-cluster

.. |supported-implementations| image:: https://img.shields.io/pypi/implementation/aws-cluster.svg?style=flat
    :alt: Supported implementations
    :target: https://pypi.python.org/pypi/aws-cluster


.. end-badges

Manage an IPyParallel cluster on AWS EC2.

* Free software: BSD license

Installation
============

::

    pip install aws-cluster

Documentation
=============

https://aws-ipyparallel-cluster.readthedocs.io/

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
