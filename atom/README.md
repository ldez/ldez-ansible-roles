# Atom

Atom installation for Ubuntu.

https://github.com/atom/atom/releases

## Requirements

No requirements.

## Role Variables

- `atom_temp_debdir`: optional
- `atom_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: atom, atom_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
