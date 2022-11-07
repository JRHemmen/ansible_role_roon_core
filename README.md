roon_core
=========

An Ansible role that installs Roon Core using the official installer script.

Requirements
------------

None.

Role Variables
--------------

database_path: This variable defines where Roon should place its database. default is /var/roon.

Dependencies
------------

None.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: roon_core
      roles:
         - { role: JRHemmen.roon_core }

License
-------

GPLv3
