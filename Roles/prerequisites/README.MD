Role Name
Prerequisites of the server

A brief description of the role goes here.

Requirements
Need to check the Ansible Master Machine Key can able to communicate to the Target Server 


Role Variables
--------------
#Changing the HostName of the Machine[ Value Of the HostName Should be add in /roles/defaults/main.yml]
#Change The TimeZone [HardCore the Value as "Asia/Kolkata"]
#Creating the user by [provide the username as variable in /role/vars/main.yml]
#if the sshd confg file is sucessfully rewrite need to restart the ssh serverics,once's its sucessfull the notify call the handlers,in handlers we worte as script for restart the ssh service, if the sshd config is not configured sucessfully it will skip the step of restart ssh service

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - prerequisites
License
-------

BSD

Author Information
------------------
galaxy_info:
  author: Ram
  description: Devops
  
