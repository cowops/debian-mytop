Debian-Mytop
============

A top clone for MySQL

Requirements
------------

This role requires a debian compliant system such as ubuntu.

Role Variables
--------------

No variables

Dependencies
------------

None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: cowops.debian-mytop }

Tasks
-----

  - Install [mytop](https://github.com/gregorg/mytop)


License
-------

BSD
