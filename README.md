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
-internet connection

Example Playbook
----------------
$ansible-playbook use-reposvr-role.yml -bK


License
-------
BSD

Author Information
------------------
KPPS
