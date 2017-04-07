Role Name
=========

Set the timezone on a Linux server.

Requirements
------------

- `timedatectl`

Role Variables
--------------

For all allowed timezone values, see `timedatectl list-timezones`.

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - { role: dunn.tz, become: yes }
```

License
-------

MIT
