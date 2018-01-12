Ansible Role 'Octopussy'
========================

Ansible Role to install/update [Octopussy](https://www.octopussy.pm) application.

[![Build Status](https://travis-ci.org/Octopussy-Project/ansible-role-octopussy.svg?branch=master)](https://travis-ci.org/Octopussy-Project/ansible-role-octopussy)

**Alpha version: contact me if you need more information**

Role Variables
--------------

```
octopussy_git_branch: "install-scripts-ansible"
```

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

None

Example Playbook
----------------

For a full installation of Octopussy:
```
- hosts: octopussy_server
  roles:
    - Octopussy-Project.octopussy
```

License
-------

BSD

Author Information
------------------

Sébastien Thébert <stt@octopussy.pm>
