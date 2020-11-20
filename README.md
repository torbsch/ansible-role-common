# Ansible Role: Common
An Ansible Role that installs tools on Linux Server/Workstations.

## Software packages
* Git
* tig
* Vim
* tmux
* htop
* pip3
* ranger
* zsh

## Dependencies
None.

## Example Playbook
- hosts: localhost
  gather_facts: yes
  connection: local
  roles:
  - ansible-role-common