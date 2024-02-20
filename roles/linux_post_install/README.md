linux_post_install
=========

This role will run a linux post install

Requirements
------------

Root access on the machines in the inventory

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

---
- name: Linux post install
  hosts: all
  connection: local

  roles:

    - role: linux_post_install 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com
