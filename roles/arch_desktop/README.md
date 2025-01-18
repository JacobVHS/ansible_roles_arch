# arch_desktop

This role sets up SDDM with my desired video theme and Hyprland.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_desktop

```
