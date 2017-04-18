# Packer

Packer installation for Ubuntu.

https://www.packer.io/downloads.html

## Requirements

No requirements.

## Role Variables

- `packer_version`: optional
- `packer_download_url`: optional
- `packer_dest`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: packer, packer_version: '1.0.0' }
```

## License

MIT

## Author Information

Ludovic Fernandez
