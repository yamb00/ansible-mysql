## yamb00 - mysql

Role to install & configure MySQL Server from binaries

#### Platforms

Currently it's been developed for, and tested on Ubuntu. It is assumed to work on other Debian distributions as well.

#### Role Variables

###### Default Variables

- 'mysql_basedir' -	path to install binary
- 'mysql_root' - path of mysql datadir and everything else

- 'mysql_utilities_url' - mysql utils paket
- 'mysql_connector_python_url' - mysql python connector paket

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
	  vars:
	    mysql_basedir: /opt/mysql
	    mysql_root: /var/lib/mysql
      roles:
         - { role: yamb00.mysql }

License
-------

BSD