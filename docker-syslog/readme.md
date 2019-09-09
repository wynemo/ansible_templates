```
host should be centos 7
$ ansible-playbook syslog.yml --extra-vars "hosts=192.168.56.103"
```

```
docker  ----log stdout----------> (capture tag) syslog server udp 54  -----------------> logrorate by day

```
