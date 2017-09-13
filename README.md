# ansible-debug
Ansible to debug various internals.

[![Build Status](https://img.shields.io/travis/feffi/ansible-debug.svg)](https://travis-ci.org/feffi/ansible-debug) [![Github All Releases](https://img.shields.io/github/downloads/feffi/ansible-debug/total.svg)](https://github.com/feffi/ansible-debug) [![GitHub forks](https://img.shields.io/github/forks/feffi/ansible-debug.svg?style=social&label=Fork)](https://github.com/feffi/ansible-debug) [![GitHub stars](https://img.shields.io/github/stars/feffi/ansible-debug.svg?style=social&label=Star)](https://github.com/feffi/ansible-debug) [![GitHub watchers](https://img.shields.io/github/watchers/feffi/ansible-debug.svg?style=social&label=Watch)](https://github.com/feffi/ansible-debug) [![Twitter Follow](https://img.shields.io/twitter/follow/feffi1.svg?style=social&label=Follow)](https://twitter.com/feffi1) [![License](http://img.shields.io/:license-mit-blue.svg)](https://github.com/feffi/ansible-debug/blob/master/LICENSE)

## Requirements
- Ansible 2.3

### ansible.cfg
```
hash_behaviour = merge
```

## Install
Just add the role to your ``requirements.yml`` file:
```yaml
- src: https://github.com/feffi/ansible-debug.git
  name: feffi.debug
```

## Role Variables
All role based variables are listed below, along with default values:

```yaml
debug:
  <not yet implemented>

```

## Dependencies
None.

## Example Playbook

```yaml
    - hosts: all
      vars:
        debug:
          <not yet implemented>
      roles:
        - { role: feffi.macos-avatar }
```
Or with local parameters:

```yaml
    - hosts: all
      roles:
        - { role: feffi.macos-avatar,
            debug: {
              <not yet implemented>
            }
          }
```

## TODO
* Ability to define debug params
* Ability to output to logfile