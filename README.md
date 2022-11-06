# Ansible Role: UOC base

[![CI](https://github.com/mnohe/ansible-role-uoc-desktop/workflows/CI/badge.svg?event=push)](https://github.com/mnohe/ansible-role-uoc-desktop/actions?query=workflow%3ACI)

An Ansible role that prepares a Debian-based machine for [UOC](https://uoc.edu) assignments.

## Requirements

The role is meant to be installed on a machine running a Debian distribution.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

- `default_user: uoc` The user name to be created.

## Dependencies

The role depends on the [uoc-base](https://github.com/mnohe/ansible-role-uoc-base) role.

## Example Playbook

Install from the system package manager:

    - hosts: dev
      roles:
        - role: mnohe.uoc-desktop

## License

MIT / BSD
