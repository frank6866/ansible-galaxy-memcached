memcached
==============

memcached deployment.


Role Variables
--------------
No required vars, the optional var as follows:

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

License
-------

MIT

