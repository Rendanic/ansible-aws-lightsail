# Ansible Collection - rendanic.lightsail_instances

Requirements
------------

The role requires AWS boto client for Ansible.

You can use the Container rendanic/ansibleaws:stable-2.9

Dependencies
------------

A list of other roles hosted on Galaxy should go here, plus any details in regards to parameters that may need to be set for other roles, or variables that are used from other roles.

Example Playbook
----------------

    # Create AWS Lightsail instances from inventory
    ---
    - hosts: test
      connection: local
      gather_facts: false
      roles:
        - lightsail_instances
