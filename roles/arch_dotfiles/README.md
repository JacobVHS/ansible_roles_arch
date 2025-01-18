# arch_dotfiles

This role clones down my git repo storing .config files.

## Usage

This can be run like this on:
```yaml
---
- name: Run the role
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_dotfiles

```
