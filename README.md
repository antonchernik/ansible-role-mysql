MySQL
=========

Ansible role for installing mysql 5.7. Tested platforms are:
* Debian 8

Requirements
------------

Debian 8 (jessie)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

debian_codename: jessie

Latest debian codename

default_mysql_root_password: [access]

Default mysql root password

default_mysql_user_login: [user]

Default MySQL user login

default_mysql_user_password: [access]

Default MySQL user password

default_mysql_port: [3306]

Default MySQL port

Dependencies
------------

None

Example 
----------------
    ---
    - hosts: all
      roles:
         - { role: antonchernik.mysql }

License
-------

MIT / BSD

Author Information
------------------

This role was created in 2017 by [Anton Chernik](https://github.com/antonchernik).
