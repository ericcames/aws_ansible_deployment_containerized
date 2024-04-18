inventory_add_servers
=========

This role will add servers to an inventory on your ansible controller

Requirements
------------

Admin Account on your Ansible Controller

Role Variables
--------------

controller_url: example.com
controller_user: mickey.mouse
controller_passwd: password

Dependencies
------------

Example Playbook
----------------

---
- name: 
  hosts: localhost
  connection: local

  roles:

    - role: inventory_add_servers 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com