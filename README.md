Role Name
=========

Ansible tole to install Percona Toolkit.
See https://www.percona.com/software/database-tools/percona-toolkit

Requirements
------------

Requires Percona Software repository enabled

Role Variables
--------------

None

Dependencies
------------

ussrlongbow.percona_repo

Example Playbook
----------------

As simple as:

    - hosts: servers
      roles:
         - role: ussrlongbow.percona_toolkit

License
-------

MIT

Author Information
------------------

Valentin Gostev (val@le.lc)
