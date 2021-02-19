# jtprogru.sysctl

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-sysctl/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprogru/ansible-role-sysctl/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprogru/ansible-role-sysctl)

Base sysctl parameters for linux server


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
