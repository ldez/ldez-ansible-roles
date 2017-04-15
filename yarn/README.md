# Yarn

Yarn installation for Ubuntu.

https://yarnpkg.com/en/docs/install

## Requirements

No requirements.

## Role Variables

- `yarn_gpg_url`: optional
- `yarn_repo`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: yarn }
```

## License

MIT

## Author Information

Ludovic Fernandez
