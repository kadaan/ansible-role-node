# Ansible Role: Node

[![Build Status](https://travis-ci.org/kadaan/ansible-role-node.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-node)

Installs node and global npm packages.

## Requirements

None.

## Role Variables

None.

## Dependencies

  - `kadaan.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.node }

## License

Apache 2.0
