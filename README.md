
# an ansible role for bind

## Variables

```
bind:
  chroot: false
  etcdir: /etc
  packagename: bind
  etcdir: /etc
  mainconfig: /etc/named.conf
  service: named
  directory: /var/named
```

## Usage

```
- hosts: all
  roles:
    - role: bind
```
