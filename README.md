ansible-riemann-packages
========================

[![Build Status](https://travis-ci.org/jmatt/ansible-riemann-packages.svg?branch=master)](https://travis-ci.org/jmatt/ansible-riemann-packages)

Install packages for Riemann deployment for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: jmatt.riemann-packages }

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-riemann-packages/blob/master/LICENSE).
