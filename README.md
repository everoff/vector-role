Ansible role Vector
=========

This role installs Vector-service to host with CentOS 7

Requirements
------------

Role Variables
--------------
Version of the Vector
```
  vector_version: "0.21.1"
```

Dependencies
------------

None.

Example Playbook
----------------

The simpliest example:
```yaml
- name: Install Vector
  hosts: vector
  roles:
    - vector-role
```

License
-------

MIT

Author Information
------------------
