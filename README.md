Install Two Memcache instances on hosts listed in "hosts" file.

Will work on Redhat or Debain based distros. 

Sessions instance will listen on 11211 with a cache size of 128MB.
Objects instance will listen on 11212 with a cache size of 1024MB.

Will globally open up needed ports - lock these down if you can.

Execute with:
ansible-playbook -k -i hosts site.yml
