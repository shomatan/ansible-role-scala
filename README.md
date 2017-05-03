Ansible Role: Scala
=========

Installs scala.

Requirements
------------

None.

Role Variables
--------------

    scala_version: 2.12.1

Dependencies
------------

- shomatan.java

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: shomatan.scala }

License
-------

MIT

Author Information
------------------

Shoma Nishitateno