# [powertools](#powertools)

Enable powertools repository on your system.

|GitHub|GitLab|Quality|Downloads|Version|
|------|------|-------|---------|-------|
|[![github](https://github.com/robertdebock/ansible-role-powertools/workflows/Ansible%20Molecule/badge.svg)](https://github.com/robertdebock/ansible-role-powertools/actions)|[![gitlab](https://gitlab.com/robertdebock-iac/ansible-role-powertools/badges/master/pipeline.svg)](https://gitlab.com/robertdebock-iac/ansible-role-powertools)|[![quality](https://img.shields.io/ansible/quality/45983)](https://galaxy.ansible.com/robertdebock/powertools)|[![downloads](https://img.shields.io/ansible/role/d/45983)](https://galaxy.ansible.com/robertdebock/powertools)|[![Version](https://img.shields.io/github/release/robertdebock/ansible-role-powertools.svg)](https://github.com/robertdebock/ansible-role-powertools/releases/)|

## [Example Playbook](#example-playbook)

This example is taken from [`molecule/default/converge.yml`](https://github.com/robertdebock/ansible-role-powertools/blob/master/molecule/default/converge.yml) and is tested on each push, pull request and release.

```yaml
---
- name: Converge
  hosts: all
  become: yes
  gather_facts: yes

  roles:
    - role: robertdebock.powertools
```

The machine needs to be prepared. In CI this is done using [`molecule/default/prepare.yml`](https://github.com/robertdebock/ansible-role-powertools/blob/master/molecule/default/prepare.yml):

```yaml
---
- name: Prepare
  hosts: all
  become: yes
  gather_facts: no

  roles:
    - role: robertdebock.bootstrap
```

Also see a [full explanation and example](https://robertdebock.nl/how-to-use-these-roles.html) on how to use these roles.


## [Requirements](#requirements)

- pip packages listed in [requirements.txt](https://github.com/robertdebock/ansible-role-powertools/blob/master/requirements.txt).

## [State of used roles](#state-of-used-roles)

The following roles are used to prepare a system. You can prepare your system in another way.

| Requirement | GitHub | GitLab |
|-------------|--------|--------|
|[robertdebock.bootstrap](https://galaxy.ansible.com/robertdebock/bootstrap)|[![Build Status GitHub](https://github.com/robertdebock/ansible-role-bootstrap/workflows/Ansible%20Molecule/badge.svg)](https://github.com/robertdebock/ansible-role-bootstrap/actions)|[![Build Status GitLab](https://gitlab.com/robertdebock-iac/ansible-role-bootstrap/badges/master/pipeline.svg)](https://gitlab.com/robertdebock-iac/ansible-role-bootstrap)|

## [Context](#context)

This role is a part of many compatible roles. Have a look at [the documentation of these roles](https://robertdebock.nl/) for further information.

Here is an overview of related roles:
![dependencies](https://raw.githubusercontent.com/robertdebock/ansible-role-powertools/png/requirements.png "Dependencies")

## [Compatibility](#compatibility)

This role has been tested on these [container images](https://hub.docker.com/u/robertdebock):

|container|tags|
|---------|----|
|[EL](https://hub.docker.com/repository/docker/robertdebock/enterpriselinux/general)|8|

The minimum version of Ansible required is 2.12, tests have been done to:

- The previous version.
- The current version.
- The development version.

If you find issues, please register them in [GitHub](https://github.com/robertdebock/ansible-role-powertools/issues)

## [License](#license)

[Apache-2.0](https://github.com/robertdebock/ansible-role-powertools/blob/master/LICENSE).

## [Author Information](#author-information)

[robertdebock](https://robertdebock.nl/)

Please consider [sponsoring me](https://github.com/sponsors/robertdebock).
