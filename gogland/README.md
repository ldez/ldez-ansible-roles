# Gogland

Gogland installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `gogland_version`: optional
- `gogland_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gogland, gogland_version: "171.3780.106" }
```

## License

MIT

## Author Information

Ludovic Fernandez
