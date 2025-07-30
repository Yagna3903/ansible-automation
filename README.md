# Ansible Automation Lab

This repository contains my Ansible experiments and reusable playbooks for different environments.

## Repo Structure:

1. inventories/ - environment-specific inventory files
2. playbooks/ - Ansible playbooks for various tasks
3. roles/ - reusable roles(e.g. nginx, docker)
4. files/ - static files or templates copied by playbooks

## Example usage:

```bash
ansible-playbook -i inventories/dev/hosts.ini playbooks/ping.yml
