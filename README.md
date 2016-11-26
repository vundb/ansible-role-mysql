Ansible Role Mysql
======================================

Ansible role to install and configure mysql service on gentoo instances.

Requirements
------------

None.

Role Variables
--------------

- `mysql_root_password`:
Password used for mysql root user.

- `mysql_config_default`:
Array with default mysql instance configuration. See
[default vars file](defaults/main.yml)

Dependencies
------------

[vundb/ansible-role-portage](https://github.com/vundb/ansible-role-portage)

Example Playbook
----------------
```
- hosts: all
  roles:
    - role: vundb-mysql
```

License
-------

MIT

Author Information
------------------

- You can find more roles in my GitHub channel [vundb](https://github.com/vundb)
- Follow me on Twitter [@vundb](https://twitter.com/vundb)
