# Ansible Role: UOC base

[![CI](https://github.com/mnohe/ansible-role-uoc-base/workflows/CI/badge.svg?event=push)](https://github.com/mnohe/ansible-role-uoc-base/actions?query=workflow%3ACI)

An Ansible role that prepares a Debian-based machine for [22.630 Computer structure](https://campus.uoc.edu/webapps/aulaca/classroom/Classroom.action?classroomId=899600&subjectId=895061) assignments at [UOC](https://uoc.edu).

## Requirements

The role is meant to be installed on a machine running a Debian distribution.

## Role Variables

Available variables are listed below, along with default values (see `defaults/main.yml`):

- `uoc_user: uoc` The user name to be created.

## Dependencies

The role depends on the [uoc-desktop](https://github.com/mnohe/ansible-role-uoc-desktop) role.

## Example Playbook

Install from the system package manager:

    - hosts: dev
      roles:
        - role: mnohe.uoc-22630

## License

MIT / BSD
