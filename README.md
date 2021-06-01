RHEL6 to RHEL7 Hot upgrade
=========


Requirements
------------
Ansible and:
          - preupgrade-assistant
          - preupgrade-assistant-el6toel7
          - redhat-upgrade-tool

Description
-----------

The process is simple, upgrade RHEL6.10 to latest RHEL7

  1. Run the "prepara.yaml" to Prepare the upgrade where we need to clean up the subscription and add the repository for upgrade tools.
 
  2. Run the "upgrade.yaml" to get the updates.



License
-------

BSD

Ede Willians / Tech Lead 
------------------
Canada Linux Team
