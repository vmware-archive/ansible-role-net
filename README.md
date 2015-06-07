# ansible-role-net

[Ansible](https://github.com/ansible/ansible) module for manipulating
DHCP and TFTP servers on CentOS and Debian.

## Requirements

This role currently supports Debian/Ubuntu and CentOS distros.

## Role Variables

Documentation here is under way . . . in flux as the vars get integrated into SuperVIO UI.

Whether to update the aptitude, yum, pacman or other package cache before running any install tasks.

## Example playbook

```
---
- name: setup net and dhcptftp roles
  hosts: net
  remote_user: ubuntu
  sudo: yes
  roles:
    - net
  vars_files:
    - vars/uianswers.yml
```

## License

TBD

## Author Information

This role was created in 2015 by [Jake Dupuy / VMware](http://www.vmware.com/).
