VMbuild Playbook
================

This Ansible playbook builds a virtual machine from a given image
in OpenStack.

Requirements
------------

The below python library requirements are needed on the host that executes this playbook.

openstacksdk
openstacksdk >= 0.12.0
python >= 2.7

Variables
--------------

vault: Ansible Vault path to be imported
os_user: Openstack user (included in vault)
os_passwd: Openstack user password (included in vault)
url: OpenStack URL
project: OpenStack project
project_domain: OpenStack project domain
user_domain: OpenStack user domain
image_name: OpenStack image name
vm_name: Virtual machine name
vm_flavour: OpenStack virtual machine flavour
vm_net: OpenStack network to connect the virtual machine
vm_vol_size: Virtual machine volume size (in GB)

License
-------

GPL3

Author Information
------------------
