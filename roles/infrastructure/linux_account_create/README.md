linux_account_create
=========

This role will create user accounts

Requirements
------------

Root access on the machines in the inventory
Vault Credential in Ansible Automation Platform
Vaulted file in the format of files/user_list_example.yml

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

---
- name: Linux account creation
  hosts: all

  roles:

    - role: linux_account_create 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com
