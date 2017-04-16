# GVM

GVM installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `golang_version`: required
- `golang_install_option`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gvm,  golang_version: "1.8.1" }
```

## License

MIT

## Author Information

Ludovic Fernandez
