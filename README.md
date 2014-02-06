# Ansible Zabbix Server Role
An ansible role for installing zabbix server

## Usage:

    ---
    - hosts: all
      remote_user: root
      roles:
      - zabbix-server

## Homepage: 

https://github.com/jdauphant/ansible-role-zabbix-server

## Informations:
- This role is base on the structure of : https://github.com/resmo/ansible-role-zabbix-agent
- Tested on Ubuntu, not on Redhat family
- Postgresql support only for the moment
