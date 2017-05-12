andrewrothstein.calicoctl
=========
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-calicoctl.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-calicoctl)

Installs calicoctl to get started with [Project Calico](https://www.projectcalico.org/)

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
    - andrewrothstein.calicoctl
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
