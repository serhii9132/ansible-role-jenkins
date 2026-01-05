ansible-jenkins
==============

Ansible role to install a Jenkins server.'

Supported platfroms:
```
- Debian 13 (Trixie)
- Ubuntu 22.04 (Jammy Jellyfish)
- Ubuntu 24.04 (Noble Numbat)
```

Requirements
------------

This role requires Ansible 2.19 or higher

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
    - serhii9132.jenkins
```

License
-------

MIT
