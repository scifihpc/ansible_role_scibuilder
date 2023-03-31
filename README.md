Role Name
=========

Install and prep SciFi-HPC Scibuilder https://github.com/scifihpc/scibuilder

Requirements
------------

The role is prepped for Redhat 9.0
Uses podman. One needs to manually get the up-to date tokens for runner installation.

Role Variables
--------------

Multiple. Please check defaults/main.yml

Dependencies
------------


Example Playbook
----------------


```
---

- name: Install scibuilder
  hosts: localhost
  remote_user: root
  become: yes

  roles: 
  - { role: ansible_role_scibuilder  } 
```

Author Information
------------------

Simppa Äkäslompolo, Aalto Scientific computing.

https://scicomp.aalto.fi/triton/help/#triton-support-team
