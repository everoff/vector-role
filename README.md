Ansible role Vector
=========

This role installs Vector-service to host with CentOS 7

Requirements
------------


Role Variables
--------------
Git repository
```
lighthouse_url: "https://github.com/VKCOM/lighthouse.git"
```
Dependencies
------------

You must install `Git` and `Nginx` to the correct work of the `Lighnhouse`.

Example Playbook
----------------

```yml
- name: Install Lighthouse
  hosts: lighthouse
  roles:
    - lighthouse-role
```


License
-------

MIT

Author Information
------------------
