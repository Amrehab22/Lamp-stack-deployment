# LAMP Stack Deployment with Ansible

This project contains an Ansible playbook to automate the deployment and configuration of a LAMP stack (Linux, Apache, MySQL, PHP) on multiple servers.

## Features
- **Apache**: Installs Apache and deploys a sample PHP file.
- **MySQL**: Installs and secures MySQL with a root password.
- **PHP**: Installs PHP and configures Apache to process PHP files.

## Setup

### 1. Install Ansible:

-sudo apt update
-sudo apt install ansible

### 2. Configure the Inventory:

-Edit the inventory/dev or inventory/prod file with the IPs or hostnames of your target servers.

### 3. Run the Playbook:

-ansible-playbook -i inventory/dev playbook.yml

### 4.How to Test the Playbook

-Once the playbook runs successfully, access the Apache server using the server’s IP address in a browser. You should see the PHP info page.



