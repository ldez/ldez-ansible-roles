# Gopass

Gopass installation for Ubuntu.

https://www.justwatch.com/gopass/#install

## Requirements

No requirements.

## Role Variables

- `gopass_version`: optional
- `gopass_temp_debdir`: optional
- `gopass_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gopass, gopass_version: '1.0.2', gopass_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
