[![Build Status](https://travis-ci.com/calvinbui/ansible-unifi.svg?branch=master)](https://travis-ci.com/calvinbui/ansible-unifi)

# Ansible Unifi

UniFi SDN Controller for Debian/Ubuntu within a Docker container. Follows the official guide from [Ubiquiti](https://help.ubnt.com/hc/en-us/articles/220066768-UniFi-How-to-Install-Update-via-APT-on-Debian-or-Ubuntu).

##  Requirements

N/A

## Role Variables

`unifi_version`: Version of Unifi to install. Must be exact.

## Dependencies


## Example Playbook

```yaml
- hosts: servers
  become: true
  roles:
    - role: calvinbui.ansible_unifi
```

## License

GPLv3

## Author Information

http://calvin.me
