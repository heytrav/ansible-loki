Ansible Loki
=========

Install Loki 

Requirements
------------



Role Variables
--------------

| Variable  |  Description                  |  Default |
| ---       |  ---                          |  --- |
| version   |  Version of the Loki library  |  v1.0.0     |

Dependencies
------------


Example Playbook
----------------


    - hosts: servers
      roles:
         - { role: ops-loki, version: v1.0.1 }

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a
website (HTML is not allowed).
