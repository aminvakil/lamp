Role Name
=========

Adds MySQL User and DB on Debian Buster

Requirements
------------

None.

Role Variables
--------------

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - role: aminvakil.mysql_add_user

License
-------

GPL-3.0

Author Information
------------------

[Amin Vakil](https://www.aminvakil.com/)
