# arch_python

This role sets up python virtual environments for all users with home directories.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_python

```
