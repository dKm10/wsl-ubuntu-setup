### This folder contains ansible playbook to configure WSL Ubuntu environment for IaC development

Tested distro
* Ubuntu-20.04
* Ubuntu-18.04

After installing your WSL distro, run below command to udpate all your system packages 
```bash
 sudo apt -y update && sudo apt -y upgrade
```

Install ansible using below command 
```bash
 sudo apt install ansible
```

clone this repository and change directory to devsetup folder, run ansible playbook using below command. This will prompt you for password, please enter the sudo password set during WSL setup
```bash
 ansible-playbook -K playbook.yml
```
