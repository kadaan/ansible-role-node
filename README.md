# Ansible Role: Node

[![Build Status](https://travis-ci.org/kadaan/ansible-role-node.svg?branch=master)](https://travis-ci.org/kadaan/ansible-role-node)

Installs node and global npm packages.

## Requirements

None.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

    node_npm_global_packages: []

Global NPM packages you would like to make sure are installed.

## Dependencies

  - `kadaan.homebrew`

## Example Playbook

    - hosts: localhost
      roles:
        - { role: kadaan.node }

## License

Apache 2.0
