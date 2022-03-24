# Ansible-Playbook1--Devops
Ansible Playbook to install Apache and git on Ubuntu

This playbook consist of 2 plays:
- 1 that installs Apache and has 5 modules(apt, file, service, ufw, copy)
- 1 that installs git and has 1 module(apt)

The playbook is created on a EC2 instance known as the Controller 
and helps to install Apache and git on other EC2 instances known as Clients 
