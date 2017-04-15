# Virtual Box

Virtual Box installation for Ubuntu.

https://yarnpkg.com/en/docs/install

## Requirements

No requirements.

## Role Variables

- `virtualbox_repo`: optional
- `virtualbox_gpg_url`: optional
- `virtualbox_version`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: virtualbox }
```

## License

MIT

## Author Information

Ludovic Fernandez
