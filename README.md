[![CircleCI](https://circleci.com/gh/andrewrothstein/ansible-supervisord.svg?style=svg)](https://circleci.com/gh/andrewrothstein/ansible-supervisord)
andrewrothstein.supervisord
===========================

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
