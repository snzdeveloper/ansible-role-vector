Role Name
=========

Deploy [Vector](https://vector.dev/) using ansible.

Requirements
------------

- Ansible >= 2.8 (It might work on previous versions, but we cannot guarantee it)

Role Variables
--------------

 - vector_version: "0.44.0"

Dependencies
------------

No dependancies

Example Playbook
----------------

Sample playbook ilustrates use case to install vector v0.50.0

- name: Install Vector
  hosts: vector
  roles:
    - vector
  vars: 
    - vector_version: "0.50.0"

License
-------

EDU

Author Information
------------------

Snzdeveloper inc. ltd. Gmbh holding

