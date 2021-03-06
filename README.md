# dolibarr

[![Build Status](https://img.shields.io/travis/infOpen/ansible-role-dolibarr/master.svg?label=travis_master)](https://travis-ci.org/infOpen/ansible-role-dolibarr)
[![Build Status](https://img.shields.io/travis/infOpen/ansible-role-dolibarr/develop.svg?label=travis_develop)](https://travis-ci.org/infOpen/ansible-role-dolibarr)
[![Updates](https://pyup.io/repos/github/infOpen/ansible-role-dolibarr/shield.svg)](https://pyup.io/repos/github/infOpen/ansible-role-dolibarr/)
[![Python 3](https://pyup.io/repos/github/infOpen/ansible-role-dolibarr/python-3-shield.svg)](https://pyup.io/repos/github/infOpen/ansible-role-dolibarr/)
[![Ansible Role](https://img.shields.io/ansible/role/25622.svg)](https://galaxy.ansible.com/infOpen/dolibarr/)

Install dolibarr package.

## Requirements

This role requires Ansible 2.2 or higher,
and platform requirements are listed in the metadata file.

## Testing

This role use [Molecule](https://github.com/metacloud/molecule/) to run tests.

Local and Travis tests run tests on Docker by default.
See molecule documentation to use other backend.

Currently, tests are done on:
- Debian Jessie
- Ubuntu Xenial

and use:
- Ansible 2.2.x
- Ansible 2.3.x
- Ansible 2.4.x
- Ansible 2.5.x

### Running tests

#### Using Docker driver

```
$ tox
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
    - { role: infOpen.dolibarr }
```

## License

MIT

## Author Information

Alexandre Chaussier (for Infopen company)
- http://www.infopen.pro
- a.chaussier [at] infopen.pro
