# ansible_role_cloudflared

An Ansible role to install and configure the cloudflared service.

## Requirements

None.

## Role Variables

* cloudflared_arch = The CPU architecture to use for cloudflared. `amd64` or `arm`. Default: `amd64`.

## Dependencies

None.

## Example Playbooks

```
---
- hosts: <HOSTS>
  roles:
    - ansible_role_cloudflared
```

## License

Apache v2.0
