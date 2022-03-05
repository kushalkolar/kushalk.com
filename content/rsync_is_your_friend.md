Title: rsync is your friend
Date: 2022-03-05 13:00
Category: Linux

`rsync` is a great and easy tool to manage backups of directories on linux filesystems! When you use `rsync`, it only copies over new data, so it allows you to easily maintain your backups much more efficiently. Therefore you don't have to overwrite massive amounts of data when updating an existing backup.

Basic Usage:

```
rsync -avP <source> <destination>
```

```
rsync -avP /work/myself/my_precious_project /share/data/archive/my_precious_project_backup
```

