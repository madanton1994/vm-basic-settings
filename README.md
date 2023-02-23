Role Name basic
=========

This role setup basic tools for docker and docker

Requirements
------------

* Python on hosts witch we need to setup
* sshpass on localhost from we must running playbooks

Role Variables
--------------

In playbook uses vars from `group_vars` directory
* `group_vars/all.yaml` - default vars

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: all
      become: true
        roles:
          - basic
