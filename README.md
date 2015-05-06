pcp-ansible
=========

Installs Performance-Copilot (PCP) on Debian/Ubuntu servers

Requirements
------------

Requires curl to be installed on the server

Role Variables
--------------

Available variables are listed below, along with defaults values (see vars/main.yml)

`pcp_install_webapi: true`

By default, this role will also install and start the pmwebd daemon.

`pcp_webapi_request_timeout: 1`

Timeout in seconds for the request between the pmwebd daemon and the pmcd daemon.


Dependencies
------------

None

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: meteorfox.pcp-ansible }

License
-------

Apache 2.0

Author Information
------------------

This role was created by Carlos Torres in 2015.