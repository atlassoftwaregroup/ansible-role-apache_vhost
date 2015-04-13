[![Build Status](https://travis-ci.org/jnakatsui/ansible-role-apache_vhost.svg?branch=master)](https://travis-ci.org/jnakatsui/ansible-role-apache_vhost)
apache\_vhosts
=========
Configures apache vhosts files

Requirements
------------
None

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that  are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------
- jnakatsui.zendserver

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: jnakatsui.apache_vhosts }

License
-------
MIT

