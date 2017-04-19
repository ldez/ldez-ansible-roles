# Slack

Slack installation for Ubuntu.

https://slack.com/downloads/linux

## Requirements

No requirements.

## Role Variables

- `slack_version`: optional
- `slack_download_url`: optional


## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: slack, slack_version: "2.5.2" }
```

## License

MIT

## Author Information

Ludovic Fernandez
