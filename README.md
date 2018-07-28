Ansible Role: OM2M
=========

Install OM2M for CentOS and Ubuntu linux.

Requirements
------------

None.

Role Variables
--------------

None.

Dependencies
------------

This role depends on:

* redtail83.git2
* redtail83.oraclejdk8
* redtail83.maven3

Example Playbook
----------------

Both CentOS 7 and Ubuntu 16.04:

    - hosts: servers
      roles:
         - { role: redtail83.om2m }

License
-------

MIT
