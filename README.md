# Ansible Automation Lab

This repository contains my Ansible experiments and reusable playbooks for different environments.

## Repo Structure:

inventories/ - environment-specific inventory files
playbooks/ - Ansible playbooks for various tasks
roles/ - reusable roles(e.g. nginx, docker)
files/ - static files or templates copied by playbooks

## Example usage:
```bash
ansible-playbook -i inventories/dev/hosts.ini playbooks/ping.yml
