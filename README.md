memoryleak.kickstart
====================

A simple role to generate kickstart files.

Requirements
------------

* pykickstart

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

The ksvalidate and ksflatten commands need to be executed by the this role.

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: memoryleak.kickstart }

License
-------

BSD

Author Information
------------------

Haydar Ciftci <haydar.ciftci@gmail.com>
