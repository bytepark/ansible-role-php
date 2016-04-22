[![Build Status](https://travis-ci.org/bytepark/ansible-role-php.svg?branch=master)](https://travis-ci.org/bytepark/ansible-role-php)

ansible-role-php
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
         - { role: bytepark.php }
      vars:
        php_version: php7.0
		server_timezone: UTC
		php_packages: [php-cli, php-gd]

License
-------

MIT

Author Information
------------------

bytepark / 2016.
