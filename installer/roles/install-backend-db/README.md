install-backend-db
=========

Openstack can use a backend database such as mySQL or PostgreSQL.  This playbook installs mySQL on the target node

Requirements
------------

None

Role Variables
--------------

db_password: openstack1  used as a default password can be overridden given -e parameters to ansible-playbook

Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      roles:
         - install-backend-db

License
-------

Apache2

Author Information
------------------

Richard Winters <rwin336@gmail.com>

