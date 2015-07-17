erln8
=====

> An Ansible role for installing [erln8](http://erln8.github.io/erln8/), the sneaky Erlang version manager.

## Requirements

None

## Role Variables

- **`erln8_version`**: the erln8 version to install (usually a tag)

## Dependencies

None

## Example Playbook

**Installing for the root user:**

```yaml
---
- hosts: all
  roles:
    - role: erln8
```

**Installing for a non-root user:**

```yaml
---
- hosts: all
  roles:
    - role: erln8
      erln8_user: web
```

## License

MIT
