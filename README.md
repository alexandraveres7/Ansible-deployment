# Ansible-deployment

The purpose of this project is to deploy an application using Ansible to a virtual machine.

For security reasons, I used ansible vault to store the password. 
You can change the ip, user and password to match the credentials of your target virtual machine from the _inventory.yaml_ file. Also, you can configure the port in which the application runs on the target virtual machine via the inventory.

To start the deploy process, run the following command:

**$ ansible-playbook -i inventory.yaml playbook.yaml --ask-vault-pass**



