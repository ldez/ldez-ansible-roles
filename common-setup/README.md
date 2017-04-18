# Common Setup

Common Setup for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `common_setup_extra_packages`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: "common-setup", common_setup_extra_packages: [ "wget" ] }
```

## License

MIT

## Author Information

Ludovic Fernandez
