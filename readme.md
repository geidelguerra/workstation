## Automate workstation provisioning and configuration using Ansible.

**Requirements**

Ansible must be installed on the system.
See [Ansible Installation Guide](https://docs.ansible.com/ansible/latest/installation_guide/intro_installation.html)

**Usage**

```ansible-playbook -K main.yml```

**What's included**

- git
- unzip (useful when installing composer dependencies)
- php 7.3 + extensions
- composer
- mariadb
- nodejs 10
- vscode + extensions

Both php and nodejs versions are defined as vars in ```group_vars/all.yml```