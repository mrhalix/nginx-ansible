# Nginx Ansible
=========

This is a playbook for deploying nginx and configure vhosts 

Requirements
------------

this playbook works base on ssh protocol so enabled ssh communication is required

so if the ssh is set on different port, and you don't have any firewall installed on your servers, and you wish the play book to configure it for you, please install the firewall yourself and add your ssh port to the firewall

How To Use
----------------

first, fill-in required information in inventory.ini and vars.yaml then run ansible-playbook command:

```bash
ansible-playbook -i inventory.ini playbook.yaml
```
