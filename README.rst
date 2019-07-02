=======
mongodb
=======

SaltStack formula for building a MongoDB replica set with access controls.

.. note::

    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

============
REQUIREMENTS
============

grains.append roles mongodb_primary (to the designated mongodb primary node to start)
grains.append roles mongodb_secondary (to the others)
pkg.install python-pip



Available states
================

.. contents::
    :local:

``mongodb``
-----------

TODO - add description of this state

``mongodb.conf``
----------------

TODO - add description of this state


Template
========

This formula was created from a cookiecutter template.

See https://github.com/mitodl/saltstack-formula-cookiecutter.
