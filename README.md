locales
=======
[![Ansible Lint](https://github.com/oxivanisher/role-locales/actions/workflows/ansible-lint.yml/badge.svg)](https://github.com/oxivanisher/role-locales/actions/workflows/ansible-lint.yml)

Configures locales on the system.

Role Variables
--------------

| Name             | Comment                           | Default value                   |
|------------------|-----------------------------------|---------------------------------|
| locales_required | Which locales should be installed | `['e_CH.UTF-8', 'en_US.UTF-8']` |

Example Playbook
----------------
```yaml
- name: Configure locales
  hosts: all
  collections:
    - oxivanisher.linux_base
  roles:
    - role: oxivanisher.linux_base.locales
```

License
-------

BSD

Author Information
------------------

This role is part of the [oxivanisher.linux_base](https://galaxy.ansible.com/ui/repo/published/oxivanisher/linux_base/) collection, and the source for that is located on [github](https://github.com/oxivanisher/collection-linux_base).
