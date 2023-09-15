# ansible-apps_unattended_upgrades

[![Galaxy Role](https://img.shields.io/badge/galaxy-apps_unattended_upgrades-purple?style=flat)](https://galaxy.ansible.com/lotusnoir/apps_unattended_upgrades)
[![Version](https://img.shields.io/github/release/lotusnoir/ansible-apps_unattended_upgrades.svg)](https://github.com/lotusnoir/ansible-apps_unattended_upgrades/releases/latest)
[![GitHub repo size](https://img.shields.io/github/repo-size/lotusnoir/ansible-apps_unattended_upgrades?color=orange&style=flat)](https://galaxy.ansible.com/lotusnoir/apps_unattended_upgrades)
[![downloads](https://img.shields.io/ansible/role/d/)](https://galaxy.ansible.com/lotusnoir/apps_unattended_upgrades)
[![Ansible Quality Score](https://img.shields.io/ansible/quality/)](https://galaxy.ansible.com/lotusnoir/apps_unattended_upgrades)
[![License](https://img.shields.io/badge/license-Apache--2.0-brightgreen?style=flat)](https://opensource.org/licenses/Apache-2.0)

## Description

Install and configure apt auto-updates (forked from https://github.com/verboEse/ansible-role-unattended-upgrades)
## Requirements

none

## Role variables

See [variables](/defaults/main.yml) for more details.

## Examples

        ---
        - hosts: apps_unattended_upgrades
          become: true
          become_method: sudo
          gather_facts: true
          roles:
            - role: ansible-apps_unattended_upgrades


## License

This project is licensed under Apache License. See [LICENSE](/LICENSE) for more details.

## Author Information

- [Philippe LEAL](https://github.com/lotusnoir)
