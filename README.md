EPEL Role
=========

This role installs the [EPEL repository](https://fedoraproject.org/wiki/EPEL#Quickstart) on a server.

Requirements
------------

* RHEL/Centos

Role Variables
--------------

The `epel_repo_pkg_url` is set in the `defaults/main.yml`.

Dependencies
------------

No dependency.

Example Playbook
----------------

```
- hosts: servers
  roles:
    - pstauffer.epel
```

License
-------

MIT

Author Information
------------------

[Pascal Stauffer](https://github.com/pstauffer)
