ansible-role-nginx
=========

Ansible role to install php

Requirements
------------

No further requirements

Role Variables
--------------

Available variables are listed below, along with default values:
	
	php_version: php7.0
	server_timezone: UTC
	php_packages: php-cli

Dependencies
------------

No dependencies

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: bytepark.ansible-role-php }
      vars:
        php_version: php7.0
		server_timezone: UTC
		php_packages: php-cli

License
-------

MIT

Author Information
------------------

bytepark / 2016.