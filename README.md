Role Name
=========

Ansible Logstash Role, by default this will take input from Filebeat and output it to Elasticsearch
Requirements
------------

* RHEL/Centos7 (Any OS utilizing Yum package manager)

Role Variables
--------------

*  elk_logstash_port: 5443

Dependencies
------------
OULibraries.elasticsearch
OULibraries.filebeat

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

[MIT](https://github.com/OULibraries/ansible-role-elk/blob/master/LICENSE)

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
