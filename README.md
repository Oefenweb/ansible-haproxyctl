## haproxyctl

[![Build Status](https://travis-ci.org/Oefenweb/ansible-haproxyctl.svg?branch=master)](https://travis-ci.org/Oefenweb/ansible-haproxyctl) [![Ansible Galaxy](http://img.shields.io/badge/ansible--galaxy-haproxyctl-blue.svg)](https://galaxy.ansible.com/list#/roles/6249)

Set up the latest version of [haproxyctl](https://github.com/flores/haproxyctl) in Debian-like systems.

#### Requirements

* `git-core` (will be installed)
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
