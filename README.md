gvisor_install
=========

This Ansible role automates the process of installing the latest version of `runsc`, the runtime for gVisor a.k.a. Google's sandboxing tool for containers, on a target machine or group of machines.

Requirements
------------

Docker must be installed on the target host.

Example Playbook
----------------

```yaml
---
- name: Install gvisor
  hosts: all
  become: true
  roles:
    - gvisor_install
```

License
-------

GPLv3

Author Information
------------------

Guillaume André: mail@guillaumea.fr
Blog: [https://blog.guillaumea.fr](https://blog.guillaumea.fr)
