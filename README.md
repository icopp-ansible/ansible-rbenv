# ansible-rbenv

Install rbenv and ruby-build via Homebrew.

This role also adds rbenv's init scripts for bash, fish, and zsh shells.

## Dependencies

* [icopp.homebrew](https://github.com/icopp/ansible-homebrew)

## Example Playbook

```
  - hosts: all
    roles:
      - role: icopp.rbenv
```

## License

MIT
