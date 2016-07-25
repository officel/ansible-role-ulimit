Ansible Role: selinx
=========

[![Build Status](https://travis-ci.org/officel/ansible-role-ulimit.svg?branch=master)](https://travis-ci.org/officel/ansible-role-ulimit)
[![Ansible Role](https://img.shields.io/badge/galaxy-officel.ulimit-blue.svg?maxAge=2592000)](https://galaxy.ansible.com/officel/ulimit/)

set(init) ulimit. for "Too many open files" error messages.

Requirements
------------

none.

Role Variables
--------------

none.

Dependencies
------------

none.

Example Playbook
----------------

    - hosts: all
      become: true
      roles:
         - officel.ulimit

License
-------

MIT / BSD

Author Information
------------------

This role was created by raki.
