Ansible Role 'Octopussy'
========================

Ansible Role to install/update [Octopussy](https://www.octopussy.pm)

**WORK IN PROGRESS - DON'T USE IT !**

Role Variables
--------------

```
octopussy_version: "1.0.16"
```

```
octopussy:
  certificate:
    common_name:       octopussy.your.org
    country_name:      FR  
    email_address:     someone@your.org
    organization_name: YourOrganisation
```

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```
- hosts: octopussy_server
  roles:
    - sebthebert.octopussy
```

License
-------

BSD

Author Information
------------------

Sébastien Thébert <stt@octopussy.pm>
