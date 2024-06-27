# Ansible setup

Prerequisite:

- Install brew
- install ansible and stow:

```sh
brew install ansible
```

Usage:

```sh
ansible-playbook --ask-vault-pass --ask-become-pass local.yaml
```
