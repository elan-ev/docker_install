Ansible: Install Docker Role
============================

This Ansible role installs the Docker CE repository and Docker itself.
It will start and enable the service so that the host is ready to run containers.


Example Playbook
----------------

Example of how to use the role:

```yaml
- hosts: all
  become: true
  roles:
    - role: elan.docker_install
```
