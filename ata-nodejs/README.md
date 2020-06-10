ATA-NodeJs
=========

Installing EPEL repo and Nginx on the server 

Requirements
------------

You need NVM and PM2

Role Variables
--------------
  vars:
    nvm_user: ec2-user
    nvm_version: "v0.35.2"
    nvm_node_version: "12.14.1"
    pm2_user: root
    pm2_startup: systemd

Dependencies
------------

  roles:
    - moviedo.nvm
    - treinberger.pm2

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

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
