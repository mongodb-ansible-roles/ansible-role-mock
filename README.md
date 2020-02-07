Ansible role for mock
==================================

Installs the mock package

[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-mock/workflows/Molecule%20Test/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-mock/actions?query=workflow%3A%22Molecule+Test%22)
[![GitHub Actions](https://github.com/mongodb-ansible-roles/ansible-role-mock/workflows/Release/badge.svg)](https://github.com/mongodb-ansible-roles/ansible-role-mock/actions?query=workflow%3A%22Release%22)


Requirements
------------

None

Role Variables
--------------

| Name | Description | Type | Default | Required |
|------|-------------|:----:|:-------:|:--------:|
| `mock_user` | User to be added to mock group | string | "" | yes |

Dependencies
------------

None

Example Playbook
----------------

```yaml
- hosts: all
  roles:
    - role: ansible-role-mock
      vars:
        mock_user: mci-exec
```

License
-------

[Apache License](LICENSE)
