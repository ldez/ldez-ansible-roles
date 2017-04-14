# Dropbox

Dropbox installation for Ubuntu.

https://www.dropbox.com/install-linux

## Requirements

No requirements.

## Role Variables

- `dropbox_version` : optional
- `dropbox_temp_debdir`: optional
- `dropbox_download_url`: optional

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
