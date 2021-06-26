# Ansible

### For server install
- add public ip to inventory file
- ansible-playbook -i inventory wireguard-server-install.yml

### For user management
- to use email, you must create an app password for a gmail account
- add a user email to create a config on the server
- delete a user email to remove a config on the server
- add public ip to inventory file
- ansible-playbook -i inventory wireguard-users.yml

