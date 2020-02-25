# Ansible Role: Install GUI dev tools

Install and configure GUI development tools

Applying this role will set up a range of GUI development tools on the machine for use as a development environment.

### Linux

- kdiff3
- X11
- xeyes (for testing X11)

### macOS


### Windows

## Requirements

None.

## Role Variables

None.

## Dependencies

None.

## Example Playbook

    - hosts: all
      roles:
        - ccdc-cpp-gui-dev-tools

## License

MIT / BSD

## Author Information

This role was created in 2020 by Claudio Bantaloukas, based on existing roles at CCDC, by Jeff Geerling and google searches