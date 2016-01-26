# mongodb-backup
Shell script for automating MongoDB backups

The backup directory should contain the following entries:

[root@ip-10-0-213-12 mongodb]# ls -lha
total 8.0K
drwxr-xr-x 7 root root 123 Jan 26 16:46 .
drwxr-xr-x 3 root root  20 Jan 26 00:30 ..
-rw-r--r-- 1 root root  11 Jan 26 16:46 backup-lastTimestamp
drwxr-xr-x 2 root root  78 Jan 26 16:46 daily
drwxr-xr-x 2 root root  42 Jan 26 16:46 latest
drwxr-xr-x 2 root root   6 Jan 26 00:30 monthly
drwxr-xr-x 5 root root 117 Jan 26 17:21 oplog
-rw-r--r-- 1 root root  11 Jan 26 17:22 oplog-lastTimestamp
drwxr-xr-x 2 root root   6 Jan 26 00:30 weekly


