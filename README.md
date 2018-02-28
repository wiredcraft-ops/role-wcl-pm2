## role-wcl-pm2
> this role requires node & npm pre-installed.

### Install

```
# requirements.yml
- src: https://github.com/wiredcraft-ops/role-wcl-pm2.git
  name: wcl-pm2
  version: master
```

```
ansible-galaxy install -r requirements.yml -p roles
```

### Example

```yaml
- hosts: all
  roles:
    - role: wcl-pm2
```