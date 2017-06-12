andrewrothstein.consul-template
===========================
[![Build Status](https://travis-ci.org/andrewrothstein/ansible-consul-template.svg?branch=master)](https://travis-ci.org/andrewrothstein/ansible-consul-template)

Installs [consul-template](https://github.com/hashicorp/consul-template)

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
    - andrewrothstein.consul-template
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
