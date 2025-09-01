Ansible Swap Role
=================

Swap creation role.

## Role Variables

- `swap_size`: The size of the swap file

## Example Playbook

```yaml
- hosts: all
  tasks:
    - ansible.builtin.include_role:
        name: ansible-swap
      vars:
        swap_size: '1G'
```

## Build & Publish

To build and publish the role, visit the GitHub Actions page of the repository and trigger the workflow "Release Package" manually.
