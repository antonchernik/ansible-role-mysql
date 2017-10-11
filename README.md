MySQL
=========

Ansible role for installing mysql 5.7. Tested platforms are:
* Debian 8
* Debian 9
* Ubuntu 16

Requirements
------------

Debian 8 (jessie)
Debian 9 (stretch)
Ubuntu 16 (xenial)

Role Variables
--------------

Available variables are listed below, along with default values (see defaults/main.yml):

| Parameter | Required | Default | Choices | Comments |
| ------------- | ------------- | ------------- | ------------- | ------------- |
| default_mysql_root_password | yes | access | | Sets MySQL user root password |
| default_mysql_user_login | yes | user | | Sets default MySQL user name |
| default_mysql_user_password | yes | access | | Sets default MySQL user password |
| default_mysql_port | yes | 3306 | | Sets MySQL server port |


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
