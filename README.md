correcthorse.favorites
=========

This role installs some common software that I use that don't need to be on production servers and don't need their own roles.

Dependencies
------------

* correcthorse.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.favorites }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
