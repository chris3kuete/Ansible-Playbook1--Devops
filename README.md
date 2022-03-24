# Ansible-Playbook1--Devops
Ansible Playbook to install Apache and git on Ubuntu

This playbook consist of 2 plays:
- 1 that installs Apache and has 5 modules(apt, file, service, ufw, copy)
- 1 that installs git and has 1 module(apt)
The playbook is created on a server known as the controller 
and helps to install Apache and git on Ubuntu clients 
