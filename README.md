PowerShell
=========

This role installs the latest version of PowerShell.

Requirements
------------

Ubuntu or Centos. Role has been tested on Centos 7 and Ubuntu 16.04.


Role Variables
--------------

```
ps_version: 6.0.0-alpha.14
```

Dependencies
------------

None.

Example Playbook
----------------

```
    - hosts: server
      roles:
         powershell
```

License
-------

MIT

Author Information
------------------
@rjongejan
Ruben J. Jongejan
