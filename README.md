riemann-packages
================

[![Build Status](https://travis-ci.org/lsst-sqre/ansible-riemann-packages.svg?branch=master)](https://travis-ci.org/lsst-sqre/ansible-riemann-packages)

Install [Riemann](http://riemann.io/) using [Ansible](http://docs.ansible.com/) for LSST SQuaRE infrastructure.

Example Playbook
----------------

    - hosts: server
      roles:
         - { role: lsst-sqre.riemann-packages }

Versions
--------

Riemann version 0.2.10 using the packages available on the website.

Tested using Ansible 2.x.

License
-------

The MIT License. See the [LICENSE file](https://github.com/lsst-sqre/ansible-riemann-packages/blob/master/LICENSE).
