ansible_platform_install
=========

This role will install and configure containerized ansible platform

Requirements
------------

Root access on the machines in the inventory
Red Hat Offline token
https://access.redhat.com/management/api
Current sha value
https://access.redhat.com/downloads/content/480/ver=2.4/rhel---9/2.4/x86_64/product-software

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

---
- name: Install and configure containerized ansible automation platform
  hosts: control

  roles:

    - role: ansible_platform_install 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com
