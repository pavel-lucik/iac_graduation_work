Role Name
=========

Role for deployment of the latest artifact from Nexus repository to QA and CI environment

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Before use this role you should define variables in defaults/main.yml:

nexus_server_ip:
nexus_server_port:
maven_repository:
maven_groupid:
maven_artifactid:
maven_extention:

java_app_group:
java_app_user:

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------

BSD

Author Information
------------------

Pavlo F.
