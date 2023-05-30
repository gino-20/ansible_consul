Role Name
=========

Ansible scripts to register and unregister services in Consul cluster

Requirements
------------

    python-consul

    requests

Usage
----------------

$ ansible-playbook -t register playbook.yml -> Register services from vars/main.yml<br>
$ ansible-playbook -t unregister playbook.yml -> Unregister services from vars/main.yml
