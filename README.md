Role Name
=========

Installs K3s on Enterprise Linux

Requirements
------------

Enterprise Linux

* At least 2GB of memory
* At least 1 cpu cores
* At least 20GB of space

Role Variables
--------------

Role Variables are set in defaults/main.yml for easy deployment

```bash


```

Dependencies
------------

no dependencies

Example Playbook
----------------

---
- name: K3s install on Enterprise Linux
  hosts: server
  become: yes
  ansible_user: user

  roles:
    - role: jesperberth.el_k3s

License
-------

BSD

Author Information
------------------

Jesper Berth