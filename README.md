# ansible_ccache_set
Project created as showcase for Travelport GDS

This ansible playbook set up shared ccache on Debian and create user which can use it.

roles:

C++_shared_cache_set
-install g++ and cache
-create shared folder for ccache
-create group which is shared for devs user
-set up desired config file

Add_dev_user
-create user which have dev group as primary
-modifie .bashrc to use g++ with ccache
