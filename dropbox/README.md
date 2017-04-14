# Dropbox

Dropbox installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `dropbox_version` : required
- `dropbox_temp_debdir`: required

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: dropbox, dropbox_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
