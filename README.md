Role Name
=========

An Ansible Role that Snowflake proxy on GNU/Linux and FreeBSD

Requirements
------------

None.

Role Variables
--------------

   clients: 0

Maximum concurrent clients by defuaults is 0 = non limit

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
          - nvjacobo.snowflake
