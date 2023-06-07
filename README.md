# bash-productivity
Bash productivity tips, files, functions.
Contains other people's work as well as my addons.

Some examples of the included .bashrc functionality:

```
cat /var/log/httpd/access_log | col 4
output:
[19/Apr/2016:11:40:10
[19/Apr/2016:11:40:23
[19/Apr/2016:11:40:55
[19/Apr/2016:11:40:55


cat /etc/passwd | col 1 :
output:
root
bin
daemon
adm
lp
sync
shutdown

cd /var/log/
s log     # bookmark current dir as 'log'
cd -
g log     # go to a bookmark 'log'
l         # list all bookmarks
log=/var/log

la /usr/local
output:
drwxr-xr-x. 17 root  root   4096 Apr  7 12:48 .
drwxr-xr-x. 14 root  root   4096 Apr  1 11:18 ..
drwxr-xr-x.  2 root  root   4096 Mar 16 15:36 bin
drwxr-xr-x   4 root  root   4096 Jun 29  2015 boost
drwxr-xr-x.  2 root  root   4096 Sep 23  2011 etc

cd /var/log
dnr         # number of files/dirs in current dir
output:
55

dnr /usr/lib
output:
35
```

