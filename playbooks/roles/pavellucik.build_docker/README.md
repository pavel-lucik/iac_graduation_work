Role Name
=========

Role for building docker image using openjdk:8-jre-alpine and latest maven artifact from the Nexus repository. Then the image is being pushed into Nexus DTR with 'latest' and 'build_number' tags.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Role Variables
--------------

Before use this role you should define variables in defaults/main.yml:

nexus_server_ip:
nexus_server_port:
nexus_server_docker_port:
maven_repository:
maven_login:
maven_password:
maven_groupid:
maven_artifactid:
maven_extention:
docker_group:
docker_user:
docker_image_name:
javapp_service_port:
build_number

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
