[![Build Status](https://travis-ci.org/wtanaka/ansible-role-haproxy.svg?branch=master)](https://travis-ci.org/wtanaka/ansible-role-haproxy)
[![CircleCI](https://circleci.com/gh/wtanaka/ansible-role-haproxy.svg?style=svg)](https://circleci.com/gh/wtanaka/ansible-role-haproxy)

wtanaka.haproxy
===============

Installs haproxy

Example Playbook
----------------

    - hosts: servers
      roles:
         - wtanaka.haproxy

### `haproxy_global_logging`

List of `log` configuration lines, one line per list item

### All variables

The full set of configuration options available are visible in
[defaults/main.yml](defaults/main.yml)

License
-------

GPLv2

Author Information
------------------

https://wtanaka.com/
