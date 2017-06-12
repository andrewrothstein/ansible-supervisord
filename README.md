andrewrothstein.supervisord
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-supervisord.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-supervisord)

A role for installing [supervisor](http://supervisord.org/) with pip

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------

```yml
- hosts: servers
  roles:
    - andrewrothstein.supervisord
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
