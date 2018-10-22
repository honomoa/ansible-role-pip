# Ansible Role: pip

The PyPA recommended tool for installing Python packages.

[https://pypi.org/project/pip/](https://pypi.org/project/pip/)

# Role Variables

```
pip_packages: []
```

pip packages to install.

# Example Playbook

```
- hosts: server
  vars:
    pip_packages:
      - awscli
      - boto
  roles:
    - { role: honomoa.pip }
```

# License
CC BY-SA 3.0
