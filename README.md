# ansible-shorewall

Installs and configures Shorewall firewall (http://shorewall.net)

## Build Status

[![Build Status](https://travis-ci.org/mrlesmithjr/ansible-shorewall.svg?branch=master)](https://travis-ci.org/mrlesmithjr/ansible-shorewall)

## Requirements

None

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

None

## Example Playbook

```yaml
- hosts: all
  become: true
  vars:
  roles:
    - role: ansible-shorewall
  tasks:
```

## License

MIT

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://twitter.com/mrlesmithjr)
- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
