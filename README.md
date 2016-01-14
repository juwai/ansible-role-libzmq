Ansible Role: libzmq
=========

Build libzmq from source on CentOS servers.

Requirements
------------

Written in Ansible 1.9.*

Role Variables
--------------

Available variables are listed below, along with default values (see `defaults/main.yml`):

### zeromq_version

Default is `4.0.5`.

You can override and install other version.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts
      roles:
         - juwai.libzmq

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2016 by [Juwai Limited](http://www.juwai.com).
