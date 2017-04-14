# SpiderOak

SpiderOak installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `spideroak_temp_debdir`: optional
- `spideroak_url`: optional
- `spideroak_gpg_key`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: spideroak, spideroak_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
