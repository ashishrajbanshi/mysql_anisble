# Task1
## Setup and configure a MySQL Database on server through Ansible.
### To install MySQL using Ansible
1. At first an EC2 instance was created using ubuntu server image.
2. Instance is connected through SSH in local machine.
3. At local machine Vagrant box is being up where ansible was installed. The public IP of EC2 server is copied in /etc/ansible/hosts file.
4. A playbook file is created where MySQL is configured. Then playbook.yml file is run using 'ansible-playbook playbook.yml -l server1 -u ubuntu' 
