vm-builder
=========

A playbook to setup a local virtual machine to create virtual machine image in Azure using 

Requirements
------------

Only testd with the environment below
- OS: CentOS7 and RHEL7
- Ansible 2.8　should be installled

Dependencies
------------

None

How to use
----------------
1.Call ansible roles to setup
  $ ansible-galaxy install -r requirements.yml -p roles
2.Execute ansible playbook
  $ ansible-playbook -i hosts site.yml
