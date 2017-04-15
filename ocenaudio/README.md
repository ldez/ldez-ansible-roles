# OcenAudio

OcenAudio installation for Ubuntu.

https://www.ocenaudio.com/download

## Requirements

No requirements.

## Role Variables

- `ocenaudio_temp_debdir`: optional
- `ocenaudio_download_url`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: ocenaudio, ocenaudio_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
