vpc_create_aws
=========

This role will create an Amazon Virtual Private Cloud (VPC).

Requirements
------------

Amazon Web Console Account
Amazon Web Services Credential in Ansible Automation Platform

Role Variables
--------------

vpc_create_aws_vpc_name: aap_containerized_deployment
vpc_create_aws_vpc_cidr: 172.16.3.0/24
vpc_create_aws_region: us-west-1
vpc_create_aws_user_name: eric.ames
vpc_create_aws_alwaysup: false
vpc_create_aws_deleteby: hercules
vpc_create_aws_ec2_ansible_group: "{{ user_name }}"
vpc_create_aws_ec2_security_group_name: "{{ vpc_name }}_SECGRP"
vpc_create_aws_ec2_vpc_subnet_name: "{{ vpc_name }}_Subnet"
vpc_create_aws_ec2_rt_name: "{{ vpc_name }}_RT_Internet"
vpc_create_aws_ec2_igw_name: "{{ vpc_name }}_IGW"
vpc_create_aws_my_email_address: "{{ user_name }}@redhat.com"

Dependencies
------------

amazon.aws

Example Playbook
----------------

---
- name: Create AWS VPC for Ansible Automation Platform deployment
  hosts: localhost
  connection: local

  roles:

    - name: vpc_create_aws

License
-------

https://spdx.org/licenses/GPL-3.0-only.html

Author Information
------------------

Eric C Ames
ericcames@msn.com
