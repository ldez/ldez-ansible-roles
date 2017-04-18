# Screen

Screen installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

No variables.

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: screen, screenrc_dest_path: "/home/{{ ansible_env.USER }}/.screenrc" }
```

## License

MIT

## Author Information

Ludovic Fernandez
