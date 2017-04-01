# Ansible Role: Base

An Ansible Role that installs base package/repositories on RHEL/CentOS/Debian.

## Dependencies

none

## Example Playbook

    - hosts: servers
      vars_files:
        - vars/main.yml
      roles:
        - { role: damienlagae.base }

*Inside `vars/main.yml`*:

    user: dlagae

## License

MIT / BSD

## Author Information

This role was created in 2016 by [Damien Lagae](mailto:damienlagae@gmail.com).