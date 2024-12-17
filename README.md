# DNBD3 Server

This Ansible repository builds, installs and configures a DNBD3 server primary or proxy server.

## Supported OS
- RockyLinux > 9
- Ubuntu > 22.0

## Example Playbook
~~~
- hosts: all
  roles:
    - { role: usegalaxy_eu.dnbd3, tags: core, dnbd3 }
~~~
