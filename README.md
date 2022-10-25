# Ansible Playbook - Potos

All inclusive, magic playbook for your custom Potos Linux Clients.

[![Test](https://github.com/projectpotos/ansible-plays-potos/actions/workflows/test.yml/badge.svg)](https://github.com/projectpotos/ansible-plays-potos/actions/workflows/test.yml)


# Dependencies

You need your own specification repository defined as with the example below `ansible-specs-potos` in the file `/etc/potos/specs_repo.yml`

```
---
client_name: "Potos Vanilla"
git_url: "git+https://github.com/projectpotos/"
git_repo: "ansible-specs-potos"
git_branch: "main"
```
