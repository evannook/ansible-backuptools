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

- pylabs.sysbase

Example Playbook
----------------

```yaml
- hosts: servers
  roles:
     - role: pylabs.backuptools
  vars:
     backuptools_borg_version: "1.1.0"
     backuptools_rclone_version: "1.38"
```

License
-------

MIT

Author Information
------------------

William Wu
