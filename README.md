# jtprog.sysctl

![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprog/ansible-role-sysctl/CI?label=CI) ![GitHub Workflow Status](https://img.shields.io/github/workflow/status/jtprog/ansible-role-sysctl/Release?label=Release) ![GitHub](https://img.shields.io/github/license/jtprog/ansible-role-sysctl)

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
     - { role: jtprog.sysctl }
```

## License

[WTFPL](LICENSE.md)

## Author Information

WWW: https://jtprog.ru
