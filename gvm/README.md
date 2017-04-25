# GVM

GVM installation for Ubuntu.

## Requirements

git.

## Role Variables

- `golang_version`: default `1.4`
- `golang_install_option`: additional GVM install command options
- `gvm_user`: remote user. Default: `ansible_env.USER`

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: gvm,  golang_version: "1.8.1", golang_install_option="--binary" }
```

## License

MIT

## Author Information

Ludovic Fernandez
