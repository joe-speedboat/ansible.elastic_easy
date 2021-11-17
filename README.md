joe-speedboat.elastic_easy
=========

Wrapper role for configuring elasticsearch nodes with the official elastic.elasticsearch role.
The basic idea is to have a "as simple as possible" role that achieves the following goals:

* compatibility with elastic.elasticsearch without customizing it
* inventory of multiple hosts will form a working cluster 
* single node inventory will form a single node cluster 
* add and/or reconfigure nodes within a cluster
* automatic bootstrapping of a new cluster
* basic best practice implemented
* more to follow...

Requirements
------------

Roles in ```roles/requirements.yml```
```ansible-galaxy role install -r roles/requirements.yml -p ./roles```

Role Variables
--------------

All variables are documented in ```defaults/main.yml```

Dependencies
------------

Documented under Requirements.

Example Playbook
----------------

Documented in ```tests``` folder.


License
-------

https://opensource.org/licenses/LGPL-3.0    
Copyright (c) Chris Ruettimann <chris@bitbull.ch>

