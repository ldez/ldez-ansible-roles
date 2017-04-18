# Vagrant

Vagrant installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `vagrant_version`: optional
- `vagrant_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: vagrant, vagrant_version: '1.9.3' }
```

## License

MIT

## Author Information

Ludovic Fernandez
