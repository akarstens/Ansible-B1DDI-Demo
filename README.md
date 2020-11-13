# Ansible-B1DDI-Demo
This is a very simple ansible demo to deploy the InfoBlox B1DDI container to a remote machine.
It assumes you have Ansible installed.
Execute with: ansible-playbook testpb.yml

~/var/default.yml: Some of the variables

testpb.yml: Highlevel playbook

~/roles/basic/tasks/main.yml: The actual set of commands

hosts : Hosts against which playbook is executed

For questions: akarstens@infoblox.com
