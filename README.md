ansible-role-pdsh-machines
=========

Installs and sets up a /etc/machines and /etc/dsh/ files for pdsh

This role is not maintained. https://github.com/jabl/ansible-role-pdsh-genders is probably better to use than this role

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

