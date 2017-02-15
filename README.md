openstack-base
==============

Base configuration before installing openstack.


Role Variables
--------------

```
# optional vars in vars/main.yml
ntp_servers:
  - "ntp1.jst.mfeed.ad.jp iburst"
  - "ntp2.jst.mfeed.ad.jp iburst"
  - "ntp3.jst.mfeed.ad.jp iburst"

```


Example Playbook
----------------

```
- hosts: all
  become: true
  roles:
    - frank6866.openstack-base
```

License
-------

MIT

