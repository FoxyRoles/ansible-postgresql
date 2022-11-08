# ansible-postgresql

Setups PostgreSQL

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.postgresql
      postgresql_version: 12 # optional, default is 12
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
