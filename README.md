# Ansible role: Monit

Forked role from ANXS Ansible Role Monit (https://github.com/ANXS/monit). 

This role latest version of Monit and configure for keep proactive monitoring of typically web services such as MySQL, nginx, in addition to others like SSHd daemon and NTP.

Requirements
------------

See [meta/main.yml](meta/main.yml)

Role Variables
--------------

See [defaults/main.yml](defaults/main.yml)

Dependencies
------------

See [meta/main.yml](meta/main.yml)


# Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yml
- hosts: servers
  roles:
    - ansible-role-monit-web
```

## License

MIT / BSD

