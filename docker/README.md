# Docker

Docker installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `docker_repo`: optional
- `docker_gpg_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: docker }
```

## License

MIT

## Author Information

Ludovic Fernandez
