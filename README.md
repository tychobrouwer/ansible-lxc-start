Start Proxmox containers
=========

This role starts Proxmox containers using the ```pct start``` command

Role Variables
--------------

The ```lxc_start_ids``` variable list should be used to set the containers which should be started.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

```yaml
    - hosts: all
      roles:
         - { role: start_containers, lxc_start_ids: [ 101, 102, 103 ] }
```

License
-------

BSD

Author Information
------------------

An optional section for the role authors to include contact information, or a website (HTML is not allowed).
