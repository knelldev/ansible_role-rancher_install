Role Name
=========

Ansible role for docker-based rancher installation and configuration on most Linux systems.

Requirements
------------

An Linux system with Python3 installed you can SSH into.

Role Variables
--------------

TBD

Dependencies
------------

```yaml
    - hosts: servers
      roles:
         - { role: knelldev.docker_install }
```

Example Playbook
----------------

```yaml
    - hosts: servers
      roles:
         - { role: knelldev.rancher_install }
```

License
-------

MIT

Author Information
------------------

Created by [knelldev](https://github.com/knelldev) in 2021
