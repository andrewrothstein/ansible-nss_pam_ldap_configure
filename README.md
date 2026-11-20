andrewrothstein.nss_pam_ldap_configure
======================================
![Build Status](https://github.com/andrewrothstein/ansible-nss_pam_ldap_configure/actions/workflows/build.yml/badge.svg)

Configure NSS/PAM for LDAP.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)

Example Playbook
----------------
```yml
- hosts: servers
  roles:
    - andrewrothstein.nss_pam_ldap_configure
```

License
-------

MIT

Author Information
------------------

Andrew Rothstein <andrew.rothstein@gmail.com>
