# Ansible Playbook - Potos

A magic all inclusive playbook for your custom linux client based on Potos

[![Test](https://github.com/projectpotos/ansible-playbook-potos/actions/workflows/test.yml/badge.svg)](https://github.com/projectpotos/ansible-playbook-potos/actions/workflows/test.yml)

# Dependencies

You need your own specification repository defined as with the example below `ansible-specs-potos` in the file `/etc/potos/specs_repo.yml`

```
---
client_name: "Potos Vanilla"
git_url: "git+https://github.com/projectpotos/"
git_repo: "ansible-specs-potos"
git_branch: "main"
```
