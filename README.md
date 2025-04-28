# Install Jenkins using Ansible

## Project Description
This project provides an **Ansible playbook** to automate the installation and setup of **Jenkins** on a Debian/Ubuntu-based system.

The playbook handles the full setup process:
- Updates system packages
- Downloads and adds Jenkins GPG key
- Adds Jenkins repository
- Installs required dependencies (fontconfig, Java)
- Installs Jenkins
- Starts and enables the Jenkins service

## Technologies Used
- Ansible
- Jenkins
- Ubuntu/Debian-based system

## How to Use

1. Make sure Ansible is installed:
   ```bash
   sudo apt update
   sudo apt install ansible -y
   
2. Save the playbook into a file, for example: install_jenkins.yml
   
3. Run the playbook:
   ```bash
   ansible-playbook install_jenkins.yml
   
4. Once completed, Jenkins will be running and accessible on port 8080.


