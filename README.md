Role Name
=========

Set up a squid server with disk cache.

Requirements
------------


Role Variables
--------------

cache_dir_size - Cache directory size in MB.

Dependencies
------------

Next revision will require Apache to display cache status.

Example Playbook
----------------

    - hosts: servers
      roles:
         - squid_server cache_dir_size=NN

License
-------

GPLv3
