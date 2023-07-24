# SQUID

Install & configure SQUID

## Requirements

```
```

## Var

```
packages:
  - squid
  - nc

squid_port: 3128
squid_proto: tcp
squid_conf: /etc/squid/squid.conf
squid_authorized_port:
  - 80
  - 443

squid_service: squid
```

## Playbook

```
- name: squid
  hosts: squid
  roles:
    - squid
```
