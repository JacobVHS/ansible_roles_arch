# Ansible Collection - jacobvhs.ansible_roles_arch

An Ansible collection to configure manage my Arch Linux machines.

## Installation
```shell
ansible-galaxy role install JacobVHS.ansible_roles_arch
```

## Usage Example
```yaml
---
- name: Base Install Arch from ISO
  hosts: localhost
  become: true
  vars:
    username: "jacob"
  roles:
    - JacobVHS.ansible_roles_arch.bootstrap_checks
    - JacobVHS.ansible_roles_arch.bootstrap_install
```
```yaml
---
- name: Arch Linux Configuration Management
  hosts: localhost
  become: true
  roles:
    - JacobVHS.ansible_roles_arch.arch_packages
    - JacobVHS.ansible_roles_arch.arch_desktop
    - JacobVHS.ansible_roles_arch.arch_network
    - JacobVHS.ansible_roles_arch.arch_dotfiles
    - JacobVHS.ansible_roles_arch.arch_python
```
```
```
```shell
ansible-playbook playbook.yaml
```

## Author
Jacob Schreuder
