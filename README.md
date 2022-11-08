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

    - name: Install Roon Core
      hosts: roon_core
      become: yes
      roles:
        - jrhemmen.roon_core
      tags:
        - roon_core
      vars:
        - database_path: "/some/other/db/path"
         ---

License
-------

GPLv3
