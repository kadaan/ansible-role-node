# Ansible Role: Node

[![CI][badge-gh-actions]][link-gh-actions]

Installs node and global npm packages.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    node_versions: []

Node versions you would like to make sure are installed by nodenv.

    node_npm_global_packages: []

Global NPM packages you would like to make sure are installed.

## Dependencies

  - `kadaan.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.node, node_execute: true }

## License

Apache 2.0

[badge-gh-actions]: https://github.com/kadaan/ansible-role-node/workflows/CI/badge.svg?event=push
[link-gh-actions]: https://github.com/kadaan/ansible-role-node/actions?query=workflow%3ACI
