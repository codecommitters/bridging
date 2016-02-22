bridging
=========

Creates a bridge interface configuration file and updates the slaves configuration

Requirements
------------

None

Role Variables
--------------

bridge: name of the Bridge interface
slave : name of the Bridge slave

Dependencies
------------

None

Example Playbook
----------------

- hosts: nc-9
  roles:
  - bridging
  vars:
  - slave: bond0.130
  - bridge: br0

License
-------

GPLv3

Author Information
------------------

John Preston [John Mille]
