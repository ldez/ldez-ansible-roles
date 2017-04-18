# Gopass

Gopass installation for Ubuntu.

https://www.justwatch.com/gopass/#install

## Requirements

No requirements.

## Role Variables

- `gopass_version`: optional
- `gopass_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gopass, gopass_version: '1.0.2'}
```

## License

MIT

## Author Information

Ludovic Fernandez
