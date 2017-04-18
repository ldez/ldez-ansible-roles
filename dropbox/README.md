# Dropbox

Dropbox installation for Ubuntu.

https://www.dropbox.com/install-linux

## Requirements

No requirements.

## Role Variables

- `dropbox_version` : optional
- `dropbox_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: dropbox, dropbox_version: '2015.10.28' }
```

## License

MIT

## Author Information

Ludovic Fernandez
