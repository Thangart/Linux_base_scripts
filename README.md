# Linux_base_scripts
Ansible script for installing base software
Build for apt based systems
Specific roles where made for codium and saltmaster / minion

## prereq
Ansible installed

apt install ansible

## usage

First download the required roles with: `ansible-galaxy install -r requirements.yml`

Then simply execute: `ansible-playbook main.yml` 