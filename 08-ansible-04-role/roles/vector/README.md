Vector
=========

This role can install Vector agent for transerring syslog to Clickhouse

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

| Vars                | Description                             |
|---------------------|-----------------------------------------|
|vector_version       |Version of Vector distrib                |
|---------------------|-----------------------------------------|
|vector_arch          |Architecture of Vector distrib           |
|---------------------|-----------------------------------------|
|clickhouse_endpoint  |IP address and port of Clickhouse Server |


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: vector }


