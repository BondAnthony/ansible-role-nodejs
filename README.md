Ansible Role Nodejs
=========

[![Build Status](https://travis-ci.org/toilops/ansible-role-nodejs.svg?branch=master)](https://travis-ci.org/toilops/ansible-role-nodejs)

Ansible role to install and configure nodejs and npm.

Requirements
------------

Currently this role only supports Redhat systems. (EL - 6,7)

Dependencies
------------

EPEL repo is required to install nodejs this role has a dependency on `toilops.config-epel-repo`

Example Playbook
----------------

Simply include this role into your playbook:
``` 
    - hosts: servers
      tasks:
        - include_role:
            name: toilops.ansible-role-install-nodejs
```
License
-------

MIT

Author Information
------------------

Find me on Github [@BondAnthony](https://github.com/BondAnthony)
