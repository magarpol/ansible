# Ansible

## Description
This repository contains Playbooks that are necessary for Server´s configuration.

## Plabooks Descriptions

### CheckMK Agent update (Linux)
This script updates CheckMK agent on servers.

### CheckMK Agent update (Windows)
This script updates CheckMK agent on servers.

### Cloud-Init configuration
This playbook configures netplan when creating a new server in IONOS Cloud Environment.

### Cloud-Init permissions
This playbook changes the cloud-init permissions on servers.

### Deploy mk_apt plugin
This playbook will delete the old version located in /plugins and create a new one with new script in /locals

### Exim4 install and configuration
This playbook installs and configures exim4 on servers.

### Exim4 checkout
This playbook checks if exim4 is installed on servers.

### Fail2ban
This playbook installs and configures fail2ban on servers.

### Install CheckMK
This playbook installs CheckMK agent on servers.

### Logwatch
This playbook installs and configures logwatch on servers.

### Logwatch log
This playbook creates a system.log from journalctl.

### Netplan install and configuration
This playbook installs and configures netplan on servers.

### Reports
This playbook creates a .txt file with all the server info on it

### Rsyslog
This playbook installs and configures rsyslog.

### Script to hosts
This playbook copy a script/archive from a shared location to a server´s folder.

### Scripts folder
This playbook creates a /scripts directory to store scripts.

### Standard packages
This playbooks reviews and install standard packages that are not installed.

### Unattended upgrades installation and configuration
This playbook installs and configures unattended-upgrades.

### Update docker gpg key
This playbook updates Docker GPG key to secure location.

### User Management
This playbook configures the Security Baselines for Linux Systems.

### xz-utils vulnerability
This playbook checks if xz-utils is installed and vulnerable, if yes, it updates the package.








