Role Name
=========
this is creating local centos repository server.

Requirements
------------
Centos Server with minimum install!
Ansible Control node and established ssh connection between managed node (repository server).

Role Variables
--------------
varialble was defined unser vars/main.yml. For now only repo path variable have.

Dependencies
------------
-

Example Playbook
----------------
$ansible-playbook tasks/main.yml 

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: username.rolename, x: 42 }

License
-------
BSD

Author Information
------------------
KPPS
