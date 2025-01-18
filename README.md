# Ansible Collection - jacobvhs.ansible_roles_arch.

An Ansible collection to configure manage my Arch Linux machines.

## Installation
```shell
ansible-galaxy role install jacobvhs.ansible_roles_arch.
```

## Usage Example
```yaml
---
- name: Base Install Arch from ISO
  hosts: localhost
  become: true
  vars:
    username: "jacob"
    root_password: "password"
  roles:
    - jacobvhs.ansible_roles_arch.bootstrap_checks
    - jacobvhs.ansible_roles_arch.bootstrap_install
```
```yaml
---
- name: Arch Linux Configuration Management
  hosts: localhost
  become: true
  roles:
    - jacobvhs.ansible_roles_arch.arch_packages
    - jacobvhs.ansible_roles_arch.arch_desktop
    - jacobvhs.ansible_roles_arch.arch_network
    - jacobvhs.ansible_roles_arch.arch_dotfiles
    - jacobvhs.ansible_roles_arch.arch_python
```
```shell
ansible-playbook playbook.yaml
```

## Galaxy Collection
[Ansible Galaxy](https://galaxy.ansible.com/ui/repo/published/jacobvhs/ansible_roles_arch/)

## Author
Jacob Schreuder
