# exim4

[![License](https://img.shields.io/badge/license-MIT%20License-brightgreen.svg)](https://opensource.org/licenses/MIT)
[![Build Status](https://travis-ci.com/Temelio/exim4.svg?branch=master)](https://travis-ci.com/Temelio/exim4)
[![Updates](https://pyup.io/repos/github/Temelio/ansible-role-exim4/shield.svg)](https://pyup.io/repos/github/Temelio/ansible-role-exim4/)
[![Python 3](https://pyup.io/repos/github/Temelio/ansible-role-exim4/python-3-shield.svg)](https://pyup.io/repos/github/Temelio/ansible-role-exim4/)
[![Ansible Role](https://img.shields.io/ansible/role/43634.svg)](https://galaxy.ansible.com/Temelio/exim4/)
[![GitHub tag](https://img.shields.io/github/tag/Temelio/ansible-role-exim4.svg)](https://github.com/Temelio/ansible-role-exim4/tags)


Install exim4 package.

## Requirements

This role requires Ansible 2.4 or higher,
and platform requirements are listed in the metadata file.

## Testing

This role use [Molecule](https://github.com/metacloud/molecule/) to run tests.

Local and Travis tests run tests on Docker by default.
See molecule documentation to use other backend.

Currently, tests are done on:
- Ubuntu Xenial
- Ubuntu Bionic

and use:
- Ansible 2.4.x
- Ansible 2.5.x
- Ansible 2.6.x
- Ansible 2.7.x

### Running tests

#### Using Docker driver

```
$ tox
```

You can also configure molecule options and molecule command using environment variables:
* `MOLECULE_OPTIONS` Default: "--debug"
* `MOLECULE_COMMAND` Default: "test"

```
$ MOLECULE_OPTIONS='' MOLECULE_COMMAND=converge tox
```

## Role Variables

### Default role variables

``` yaml
```

## Dependencies

None

## Example Playbook

``` yaml
- hosts: servers
  roles:
    - { role: Temelio.exim4 }
```

## License

MIT

## Author Information

Lise Machetel (for Temelio company)
- https://temelio.com
- lise.machetel [at] temelio.com
