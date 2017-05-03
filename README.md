memcached
==============

memcached deployment.


Role Variables
--------------
No required vars, the optional variables and its default values as follows:

```
memcached_port: 11211
memcached_user: memcached
memcached_maxconn: 1024
memcached_cachesize: 64
memcached_ipv4_address: 0.0.0.0
```


Example Playbook
----------------

```
- hosts: memcached
  become: true
  roles:
    - /path/to/memcached
```

Verify memcached
----------------
```
$ memcached-tool 192.168.168.201:11211 stats
#192.168.168.201:11211 Field       Value
         accepting_conns           1
               auth_cmds           0
             auth_errors           0
                   bytes           0
              bytes_read           7
           bytes_written           0
              cas_badval           0
                cas_hits           0
              cas_misses           0
......
......
```


License
-------

MIT

