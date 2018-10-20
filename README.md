[![Build Status](https://travis-ci.org/NINEJKH/ansible-role-git.svg?branch=master)](https://travis-ci.org/NINEJKH/ansible-role-git)

# NINEJKH.git

An Ansible role that installs git (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
git_version: 2.19.1
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: git
  roles:
    - { role: NINEJKH.git }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[9JKH (Pty) Ltd.](https://9jkh.co.za)
