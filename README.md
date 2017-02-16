openstack-base
==============

memcached deployment.


Role Variables
--------------
没有必须设置的变量, 可选的变量如下

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
- hosts: all
  become: true
  roles:
    - frank6866.memcached
```

License
-------

MIT

