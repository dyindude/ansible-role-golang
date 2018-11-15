dyindude.golang
=========

Ansible role for installing and setting up a working golang distribution on a machine. Modeled after the official golang [docker images](https://hub.docker.com/_/golang/).

Role Variables
--------------
defaults:
```
golang_gopath: "/go"
golang_version: "1.11.2"
golang_arch: "linux-amd64"
```

Example Playbook
----------------

    - hosts: servers
      roles:
         - dyindude.golang

License
-------

BSD

Author Information
------------------

dyindude
