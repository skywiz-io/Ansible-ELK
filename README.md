Ansible-ELK
=========

Ansible role to install ELK stack in Redhat 7 / CentOS 7 environments

Requirements
------------

CentOS 7 / Redhat 7

Role Variables
--------------

Package version can be modified in defaults/main.yml
In the same file, username and password can be changed. 


Example Playbook
----------------

    - hosts: monitoring
      sudo: yes
      roles:
         - { role: "ansible-elk" }

License
-------

BSD


