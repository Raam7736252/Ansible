Role Name ShellScript's of the server

A brief description of the role goes here.

The playbook within these roles has the capability to clone any repository from Git. It systematically searches for shell scripts within the cloned repository, 
collects those shell scripts, grants them execute permissions, and, in the end, establishes a cron job for the specified shell script. 

Requirements 
 Need git Acess and tocken for private repo login

Role Variables

We have to Provide the git repo url and cloning repo Destination

Example Playbook

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

- hosts: servers
  roles:
     - ShellScript's

License

BSD
Author Information

galaxy_info: author: Ram description: Devops
