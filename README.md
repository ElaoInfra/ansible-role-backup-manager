<img src="http://www.elao.com/images/corpo/logo_red_small.png"/>

# Ansible Role: elao.backup-manager

This role will assume the setup of [backup-manager](https://github.com/sukria/Backup-Manager).

It's part of the ELAO [Ansible stack](http://ansible.elao.com) but can be used as a stand alone component.

## Requirements

- Ansible 1.9.0+

## Dependencies

None.

## Installation

Using ansible galaxy:

```bash
ansible-galaxy install elao.backup-manager
```
You can add this role as a dependency for other roles by adding the role to the meta/main.yml file of your own role:

```yaml
dependencies:
  - { role: elao.backup-manager }
```

## Role Variables

| Name                                | Default                      | Type   | Description          |
| ----------------------------------- | ---------------------------- | ------ | -------------------- |


### Configuration example

```yaml
```

## Example playbook

    - hosts: servers
      roles:
         - { role: elao.backup-manager }

# Licence

MIT

# Author information

ELAO [**(http://www.elao.com/)**](http://www.elao.com)
