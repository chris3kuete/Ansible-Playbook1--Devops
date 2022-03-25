# Ansible-Playbook1--Devops
Ansible Playbook to Setup an Apache Webserver and 
Install GIT on the Ubuntu clients.

This playbook consist of 2 PLAYS:
-PLAY 1: that installs Apache and has 5 modules(apt, file, service, ufw, copy)
-PLAY 2: that installs git and has 1 module(apt)

The playbook is created on a EC2 instance known as the Controller 
and helps to install Apache and Git on other EC2 instances known as Clients 
