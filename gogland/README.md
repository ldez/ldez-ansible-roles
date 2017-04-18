# Gogland

Gogland installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `gogland_version`: optional
- `gogland_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gogland, gogland_version: "171.3780.106", gogland_dest: : "/opt/", gogland_symlink: "/opt/gogland" }
```

## License

MIT

## Author Information

Ludovic Fernandez
