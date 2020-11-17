# ansible-workstation
A collection of roles and files I use to setup my workstation.

# How to use
These directions and the playbooks assume you are logged in as the user you wish to configure your workstaiton for and you have already given yourself sudo permissions.  They also assume you are running the plabooks locally.  To run the playbook use:
```
ansible-playbook --ask-become-pass -i inventory workstation.yml
```
