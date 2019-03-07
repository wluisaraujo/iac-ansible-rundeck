[![Build Status](https://travis-ci.org/wluisaraujo/iac-ansible-rundeck.svg?branch=master)](https://travis-ci.org/wluisaraujo/iac-ansible-rundeck)
---
# IaC: with [Ansible](https://www.ansible.com) role to install and configure [NTP Server](www.ntp.org/)
------------

Description
------------

 * Stands up Rundeck on RHEL/CentOS
 
Requirements
------------

 * Java
 * Rundeck Repo

Role Variables
--------------

[defaults/main.yml](defaults/main.yml)

Dependencies
------------

* None

Example Playbook
----------------
```yaml
---
- hosts: localhost
  vars:
    - name: value
  roles:
    - iac-ansible-rundeck
```

License
-------

[GPLv3](https://www.gnu.org/licenses/gpl-3.0.pt-br.html)
