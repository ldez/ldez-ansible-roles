# Powerline Fonts

Powerline Fonts installation for Ubuntu.

https://github.com/powerline/fonts

## Requirements

No requirements.

## Role Variables

- `powerline_fonts_force`: optional
- `powerline_fonts_checked_font`: optional
- `powerline_fonts_global_dest_path`: optional
- `powerline_fonts_git_repository`: optional
- `powerline_fonts_dest_path`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: "powerline-fonts"}
```

## License

MIT

## Author Information

Ludovic Fernandez
