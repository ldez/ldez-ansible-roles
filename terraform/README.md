# Terraform

Terraform installation for Ubuntu.

https://www.terraform.io/downloads.html

## Requirements

No requirements.

## Role Variables

- `terraform_version`: optional
- `terraform_download_url`: optional
- `terraform_dest`: optional

## Dependencies

No dependencies.

## Example Playbook

```yml
- hosts: servers
  roles:
     - { role: terraform, terraform_version: '0.9.3' }
```

## License

MIT

## Author Information

Ludovic Fernandez
