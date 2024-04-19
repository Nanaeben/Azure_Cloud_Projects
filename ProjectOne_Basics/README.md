Project 1 - Basic
Deploy an infrastructure with the following components - Azure Firewall, VM, Bastion, VNet

Procedure:
- Create a Subscription (azuresubscription) and Resource Group (Cloudprojects).
- Create Virtual Network (VNet) and setup Azure Firewall and Azure Bastion with Public Ip address
- Create a VM with Ubuntu OS and install nginx webserver on it
- Connect the VM to the VNet and configure the firewall to only allow one user (IP) to access the VM
- Configure Source, Destination IPs and ports
- Connect to the VM using Bastion and SSH pem key