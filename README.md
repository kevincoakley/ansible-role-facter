ansible-role-facter
===================

[![Build Status](https://travis-ci.org/kevincoakley/ansible-role-facter.svg?branch=master)](https://travis-ci.org/kevincoakley/ansible-role-facter)

Installs facter on host then regathers facts. Useful for getting facts from Docker containers that 
are not present in the list of Ansible facts, like the container's private ip address.

Requirements
------------

None. Tested on CentOS 7 and Ubuntu 16.04. Will probably work on any OS with apt or yum.

Role Variables
--------------

None.

Dependencies
------------

None.

Example Playbook
----------------

    - hosts: servers
      roles:
         - ansible-role-facter

License
-------

BSD

Author Information
------------------

Kevin Coakley (https://github.com/kevincoakley)
