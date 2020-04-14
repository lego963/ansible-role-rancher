[![Build Status](https://travis-ci.org/github/lego963/ansible-role-rancher.svg?branch=master)](https://travis-ci.org/github/lego963/ansible-role-rancher)

Ansible Role: Rancher
=========

Role to install (_by default_) `rancher` on **Debian** and **Ubuntu** systems.

Role Variables
--------------

```yaml
docker_version: "19.03"
rancher_image: "rancher/rancher:latest"
```

Example Playbook
----------------

For default behaviour of role (i.e. installation of **rancher**) in ansible playbook.

```yaml
- hosts: localhost
  roles:
    - lego963.rancher
```

License
-------

Apache-2.0
