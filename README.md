correcthorse.nginx
=========

An ansible role for installing nginx.

Role Variables
--------------

| Variable			| Default			| Notes				|
| :---				| :---				| :---				|
| nginx_upstream_repo		| false				| 				|
| nginx_user			| nginx				|				|
| nginx_worker_processes	| 1				|				|
| nginx_error_log		| /var/log/nginx/error.log	|				|
| nginx_pid			| /run/nginx.pid		|				|
| nginx_worker_connections	| 1024				|				|

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: correcthorse.nginx }

License
-------

MIT

Author Information
------------------

* [Joshua Rusch](https://correct.horse/)
