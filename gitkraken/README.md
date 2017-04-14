# GitKraken

GitKraken installation for Ubuntu.

https://www.gitkraken.com/download

## Requirements

No requirements.

## Role Variables

- `gitkraken_temp_debdir`: optional
- `gitkraken_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gitkraken, gitkraken_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
