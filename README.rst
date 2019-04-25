================
kibana-formula
================

This sets up kibana. Supports versions 4.5 to 7.x.


    See the full `Salt Formulas installation and usage instructions
    <http://docs.saltstack.com/en/latest/topics/development/conventions/formulas.html>`_.

Available states
================


``kibana``
------------

Installs the kibana package, and starts the associated kibana service.


Testing
=======

Testing is done with `Test Kitchen <http://kitchen.ci/>`_
for machine setup and `testinfra <https://testinfra.readthedocs.io/en/latest/>`_
for integration tests.

Requirements
------------

* Python
* Ruby
* Docker

::

    pip install -r requirements.txt
    gem install bundler
    bundle install
    bundle exec kitchen test
