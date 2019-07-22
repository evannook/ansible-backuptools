backuptools
===========

Backup tools setup

Dependencies
------------

- pylabs.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: pylabs.backuptools
  vars:
    borg_version: "1.1.10"
    rclone_version: "1.48.0"
```

License
-------

MIT

Author Information
------------------

William Wu
