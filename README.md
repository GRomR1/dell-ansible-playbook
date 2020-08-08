# dell-ansible-playbook
Configuration a Dell-EMC OS9 Networking device (S-4048) with Ansible playbooks

Read a full article of this repo:

## Prerequisite

1. Edit `hosts`-file
2. Download Galaxy roles - `ansible-galaxy install -r ansible-roles/dellemc_roles.yml`
3. Change host_vars for the device
4. Run a Playbooks

## Tested on

* Dell Switch S4048 (OS9 Network System v.9.14)
* Ansible 2.9.11 with Python 3.8

## Playbooks

1. [`dell-switch-modules`][./dell-switch-modules.yml] - examples with basic `dellos9` modules
2. [`dell-switch-galaxy`][./dell-switch-galaxy.yml] - examples of running Galaxy roles

## Links
* https://github.com/Dell-Networking/ansible-dellos-examples
* https://readthedocs.org/projects/ansible-dellos-docs/downloads/pdf/latest/
* https://docs.ansible.com/ansible/latest/modules/list_of_network_modules.html#dellos9
