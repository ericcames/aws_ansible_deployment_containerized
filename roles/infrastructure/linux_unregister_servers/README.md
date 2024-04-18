linux_unregister_servers
=========

This will unregister the server from Insights and the Customer Portal.

Requirements
------------

Role Variables
--------------

Dependencies
------------

Example Playbook
----------------

---
- name: Linux unregistration
  hosts: all
  connection: local

  roles:

    - role: linux_unregister_servers 

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com
