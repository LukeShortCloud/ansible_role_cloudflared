# ansible_role_cloudflared

An Ansible role to install and configure the cloudflared service. After setting up the `cloudflared` service, the DNS resolver `/etc/resolv.conf` needs to be manually updated to use `nameserver 127.0.0.1`.

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
