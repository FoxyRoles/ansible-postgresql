# ansible-postgresql

Setups PostgreSQL

### Example playbook
```yaml
---
- hosts: myserver
  roles:
    - role: sunfoxcz.postgresql
      postgresql_version: 15 # optional, default is 15
```

## License

Licensed under MIT license. See [LICENSE](LICENSE.md) for details.
