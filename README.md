[![Build Status](https://travis-ci.org/lifeofguenter/ansible-role-git.svg?branch=master)](https://travis-ci.org/lifeofguenter/ansible-role-git)

# lifeofguenter.git

An Ansible role that installs git (from source) on Debian-like systems.

## Requirements

none

## Role Variables

```yaml
git_version: 2.15.0
```

## Dependencies

none

## Example Playbook

```yaml

- hosts: git
  roles:
    - { role: lifeofguenter.git }
```

## License

Licensed under the MIT License. See the [LICENSE file](LICENSE) for details.

## Author Information

[Gunter Grodotzki](https://lifeofguenter.de)
