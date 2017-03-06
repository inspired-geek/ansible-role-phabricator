Ansible Role: Phabricator
=========

Installs [Phabricator](https://www.phacility.com/phabricator/) development platform to run with php-fpm behind nginx.

Requirements
------------

Requirements for now include RHEL or CentOS 6 or 7.

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

Dependencies include:
* pcextreme.mariadb
* geerlingguy.nginx

No additional config is required.

License
-------

BSD
