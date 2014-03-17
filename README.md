Install Two Memcache instances on listed hosts.

Sessions instance will listen on 11211 with a cache size of 128MB.
Objects instance will listen on 11212 with a cache size of 1024MB.

Will globally open up needed ports - lock these down if you can.

Needs Ansible version >1.6.  
