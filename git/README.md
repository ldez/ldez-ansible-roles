# Git

Git installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `git_ppa` : optional
- `git_email`: required
- `git_name`: required
- `git_signingkey`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: git, git_email: foo@bar.com, git_name: Foo Bar }
```


## License

MIT

## Author Information

Ludovic Fernandez
