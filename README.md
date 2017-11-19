Ansible Role: Docker CE
=========

Setup latest stable version of Docker CE.

Requirements
------------

None.

Role Variables
--------------

Remote user

```
remote_user: root
```

Dependencies
------------

None.

Example Playbook
----------------


    $ cat inventory
    [servers]
    172.10.10.1

    $ cat playbook.yml
    - name: "Install Docker CE"
      hosts: servers
      roles:
        - { role: mlabouardy.docker }

License
-------

MIT

Author Information
------------------

Mohamed Labouardy ([@mlabouardy](https://twitter.com/mlabouardy))
