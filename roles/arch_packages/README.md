# arch_packages

This role installs base line packages I use generally for arch linux.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_packages

```
