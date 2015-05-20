Hipache
=========

An ansible role to install a [hipache](https://github.com/hipache/hipache) server.

Requirements
------------

Only tested on Ubuntu 14.04.


Role Variables
--------------

`redis_host` hostname of redis instance.

`redis_port` port that the redis instance listens on.

Dependencies
------------

* None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: hipache-server
      roles:
         - { role: hipache, redis_host: 127.0.0.1, redis_port: 6379 }

License
-------

See `LICENSE` file.
