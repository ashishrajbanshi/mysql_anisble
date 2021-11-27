# Task1
## Setup and configure a MySQL Database on server through Ansible.

### To install MySQL using Ansible

1. At first an EC2 instance was created using ubuntu server image.
2. Instance is connected through SSH in local machine.
3. At local machine Vagrant box is being up where ansible was installed. The public IP of EC2 server was copied in /etc/ansible/hosts file.
4. A playbook file is created where MySQL was configured. Then playbook.yml file is run using 'ansible-playbook playbook.yml -l server1 -u ubuntu' to install on EC2 server.
5. On EC2 server MySQL version is checked to verify the installation.

### To give Acess and Privileges in MySQL

1. First MySQL command line was entered using root access.
2. Then two databases named "database1" and "database2" are created.
3. A "user1" was created. Read only access was granted to user1 on database1.
4. A table1 was created in database2.
5. Now, Read-Write priviliges was granted for user1 on table1 of database2.
6. A user2 was created with all the privileges on both the databases.
7. user2 created a table "devops" in database1.
8. Values are inserted in both the databases.

