# Slack

Slack installation for Ubuntu.

https://slack.com/downloads/linux

## Requirements

No requirements.

## Role Variables

- `slack_download_url`: optional
- `slack_temp_debdir`: optional


## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: slack, slack_temp_debdir: "/home/{{ ansible_env.USER }}/Downloads" }
```

## License

MIT

## Author Information

Ludovic Fernandez
