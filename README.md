Role Name
=========

A brief description of the role goes here.

Requirements
------------

Any pre-requisites that may not be covered by Ansible itself or the role should be mentioned here. For instance, if the role uses the EC2 module, it may be a good idea to mention in this section that the boto package is required.

Molecule
--------
Create your role via cookiecutter and this template!
```
$ pip install cookiecutter
$ cd ~/my/ansible/roles
$ cookiecutter https://github.com/boolman/ansible-role-template.git
You've downloaded /home/boolman/.cookiecutters/molecule-template before. Is it okay to delete and re-download it? [yes]: yes
role_name [role_name]: myrole123
scenario_name [default]:
author [your name]: boolman
description [your description]: very important stuff
company [your company (optional)]:
Select license:
1 - BSD
2 - MIT
3 - GPLv2
4 - GPLv3
5 - Apache
6 - CC-BY
Choose from 1, 2, 3, 4, 5, 6 [1]: 2
min_ansible_version [2.9]:
$ cd myrole123
$ molecule test # För att testa default ( docker lokalt ) 
$ molecule test -s vmware # För att testa mot vmware ( Glöm inte source .vmware.sh ) 
```

Role Variables
--------------

A description of the settable variables for this role should go here, including any variables that are in defaults/main.yml, vars/main.yml, and any variables that can/should be set via parameters to the role. Any variables that are read from other roles and/or the global scope (ie. hostvars, group vars, etc.) should be mentioned here as well.

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

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
