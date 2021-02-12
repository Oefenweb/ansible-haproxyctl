## haproxyctl

[![CI](https://github.com/Oefenweb/ansible-haproxyctl/workflows/CI/badge.svg)](https://github.com/Oefenweb/ansible-haproxyctl/actions?query=workflow%3ACI)
[![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-haproxyctl-blue.svg)](https://galaxy.ansible.com/Oefenweb/haproxyctl)

Set up the latest version of [haproxyctl](https://github.com/flores/haproxyctl) in Debian-like systems.

#### Requirements

* `git` (will be installed)
* `ruby` (will be installed)
* `lsof` (will be installed)

#### Variables

* `haproxyctl_install_path`: [default: `/usr/local/bin`]: Install directory

## Dependencies

None

#### Example

```yaml
---
- hosts: all
  roles:
    - haproxyctl
```

#### License

MIT

#### Author Information

* Mischa ter Smitten

#### Feedback, bug-reports, requests, ...

Are [welcome](https://github.com/Oefenweb/ansible-haproxyctl/issues)!
