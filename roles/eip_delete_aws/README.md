eip_delete_aws
=========

This role will delete the containerized ansible automation platform.

Requirements
------------

Amazon Web Console Account
Amazon Web Services Credential in Ansible Automation Platform

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

---
- name: Delete Elastic IP addresses at aws
  hosts: localhost
  connection: local

  roles:

    - role: eip_delete_aws 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com