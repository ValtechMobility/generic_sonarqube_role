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

    generic_sonarqube_jdbc_url
    generic_sonarqube_jdbc_username
    generic_sonarqube_jdbc_password

Variables that have to be set by your own.

    generic_sonarqube_ldap_username
    generic_sonarqube_ldap_password




Dependencies
------------

None

Example Playbook
----------------

    ---
    - hosts: all
      roles:
        - generic_sonarqube_role