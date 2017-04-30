# IntelliJ

IntelliJ installation for Ubuntu.

## Requirements

No requirements.

## Role Variables

- `intellij_version`: default `2017.1.2`
- `intellij_community_patch_version`: default  `171.4249.39`.
  - You must provide this version for community edition.
  - check version here: https://confluence.jetbrains.com/display/IDEADEV/EAP
- `intellij_symlink`: default `/opt/intellij`
- `intellij_dest`: default `/opt/`
- `intellij_distribution`: `community` or `EAP`. default `community`

## Dependencies

No dependencies.

## Example Playbook

For community:

```
- hosts: servers
  roles:
     - { role: intellij, intellij_distribution: "community", intellij_version: "2017.1.2", intellij_community_patch_version: "171.4249.39", intellij_symlink: "/opt/intellij", intellij_dest: "/opt/" }
```

For EAP:
```
- hosts: servers
  roles:
     - { role: intellij, intellij_distribution: "EAP", intellij_version: "171.4424.14", intellij_symlink: "/opt/intellij", intellij_dest: "/opt/" }
```

## License

MIT

## Author Information

Fernandez Ludovic
