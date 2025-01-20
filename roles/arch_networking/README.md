# arch_networking

This role handles basic network configuration of my Arch pc.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_networking

```
