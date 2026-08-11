# jtprogru.sysctl

[![CI](https://img.shields.io/github/actions/workflow/status/jtprogru/ansible-role-sysctl/ci.yml?branch=master&label=CI)](https://github.com/jtprogru/ansible-role-sysctl/actions/workflows/ci.yml) [![Release](https://img.shields.io/github/actions/workflow/status/jtprogru/ansible-role-sysctl/release.yml?label=Release)](https://github.com/jtprogru/ansible-role-sysctl/actions/workflows/release.yml) ![License](https://img.shields.io/github/license/jtprogru/ansible-role-sysctl)

Base sysctl parameters for linux server

## Requirements

The role uses the `ansible.posix.sysctl` module, so the `ansible.posix` collection must be installed:

```bash
ansible-galaxy collection install -r requirements.yml
```

## Role Variables

See `defaults`

## Example Playbook

```yaml
---
- name: Configure sysctl
  hosts: all
  become: yes
  gather_facts: yes

  roles:
     - jtprogru.sysctl
```

## License

[WTFPL](LICENSE.md)

## Author Information

WWW: https://jtprog.ru
