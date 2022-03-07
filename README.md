Sonarqube
=========

A role to deploy Sonarqube in a Docker container.

Requirements
------------

- Docker
- Postgresql database

Role Variables
--------------

For all variables please see `defaults/main.yml`.


Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_sonarqube_role