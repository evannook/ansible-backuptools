backuptools
===========

Backup tools setup


Role Variables
--------------

```yaml
backuptools_borg_version = BORGBACKUP_VERSION
backuptools_rclone_version = RCLONE_VERSION
```

Dependencies
------------

- evannook.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: evannook.backuptools
```

License
-------

MIT

Author Information
------------------

Evan Nook
