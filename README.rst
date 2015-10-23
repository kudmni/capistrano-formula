================
capistrano-formula
================

A saltstack formula for capistrano installation (Debian only)

Available states
================

.. contents::
    :local:

``capistrano``
----------

Installs ruby (v1.9.3), rubygems, net-ssh (v2.9.2) and capistrano (v2.15.5 as default).

Example Pillar
================

.. code:: yaml

    capistrano:
      version: 2.15.5
