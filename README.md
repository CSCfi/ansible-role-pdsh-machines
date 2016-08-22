ansible-role-pdsh-machines
==========================

Installs pdsh and sets up a /etc/genders based on ansible groups.

Requirements
------------

 - A repo installed on the machine that have the pdsh dependencies.
 - A hosts file with groups

Role Variables
--------------

see defaults/main.yml

Dependencies
------------


Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: ansible-role-pdsh-machines }

License
-------

MIT

Author Information
------------------

https://github.com/martbhell
https://github.com/jabl
