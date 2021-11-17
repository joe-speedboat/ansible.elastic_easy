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

This role follows the principal of unix/linux that says one tool is doing one thing, 
but this single thing, it does in a simple and clean way.
Altought I tried to achieve the target, your feedback by pull requests and issue requests are highly welcome.
Since elasticsearch is still a complex thin, do not expect to get free consulting here ...
But for good money, we do good consulting as well :-)

Cheers
Chris

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

