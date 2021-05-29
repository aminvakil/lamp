Role Name
=========

httpd_initial

Requirements
------------

None.

Role Variables
--------------
`sysadmin_email`: your-email (default=info@example.org)

`https`: false/true (default=false)

`cloudflare`: false/true (default=false)

`staging`: false/true (default=true)

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      become: true
      roles:
         - role: aminvakil.httpd_initial

License
-------

GPL-3.0

Author Information
------------------

[Amin Vakil](https://www.aminvakil.com/)
