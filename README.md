# Ansible-deployment

The purpose of this project is to deploy an application using Ansible to a virtual machine.

For security reasons, I used ansible vault to store the password. 
You can change the ip and password to match the credentials of your vm from the _inventory.yaml_ file.

To start the deploy process, run the following command:

**$ ansible-playbook -i inventory.yaml playbook.yaml --ask-vault-pass**



