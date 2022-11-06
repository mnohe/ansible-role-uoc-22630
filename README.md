# Ansible Role: UOC base

[![CI](https://github.com/mnohe/ansible-role-uoc-base/workflows/CI/badge.svg?event=push)](https://github.com/mnohe/ansible-role-uoc-base/actions?query=workflow%3ACI)

An Ansible role that prepares a Debian-based machine for [UOC](https://uoc.edu) assignments.

## Requirements

The role is meant to be installed on a machine running a Debian distribution.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

- `default_user: uoc` The user name to be created.

## Dependencies

None.

## Example Playbook

Install from the system package manager:

    - hosts: dev
      roles:
        - role: mnohe.uoc-base

## License

MIT / BSD
