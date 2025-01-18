# bootstrap_checks

This role does some pre-flight checks before bootstrapping arch linux.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.bootstrap_checks
```
