## Ansible

### What is Ansible?

- Ansible is an open-source automation tool used for configuring and managing computers, networks, and other systems. 

- It falls under the category of configuration management and application deployment tools.

- Ansible automates tasks such as application deployment, cloud provisioning, configuration management, and workflow automation.

### Installing Ansible 

Step 1: Launch an EC2 instance 

Step 2: SSH into GitBash terminal 

Step 3: Run the following commands

```
Sudo apt update
Sudo apt upgrade 
sudo apt install software-properties-common
sudo apt-add-repository ppa:ansible/ansible
sudo apt update -y
sudo apt install ansible -y
 cd /etc/ansible/
sudo apt install tree -y
Tree
cd ~/.ssh

```

### Copying the pem file 

1. Open a new GitBash terminal 

```
scp -i "~/.ssh/tech254.pem" ~/.ssh/tech254.pem ubuntu@<Insert public DNS of instance>:~/.ssh
```