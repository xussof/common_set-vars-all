common_set-vars-all

=========

This role it's intended to set a common vars file. It's like an group_vars/all.yml
You will need also another set-vars-all refering to the project is going to be developed.
like common_arsolute-set-vars-all. To set specific project vars.

Requirements
------------

All dependencies will appear on requirements.yml file

Role Variables
--------------

Dependencies
------------

All dependencies will appear on requirements.yml file

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: common_set-vars-all }

License
-------

BSD

Author Information
------------------
Made by @sergi-canas
