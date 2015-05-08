correct.horse.favorites
=========

This role installs some common software that I use that don't need to be on production servers and don't need their own roles.

Dependencies
------------

* correct.horse.common

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: favorites }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
