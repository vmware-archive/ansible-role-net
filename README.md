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

# License and Copyright
 
Copyright 2015 VMware, Inc.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.

## Author Information

This role was created in 2015 by [Jake Dupuy / VMware](http://www.vmware.com/).
