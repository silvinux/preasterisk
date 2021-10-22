Pre-Asterisk
=========

Role to prepare server to install asterisk over rhel dist like.

Requirements
------------

It must have installed some collections before run it.

Role Variables
--------------

asterisk_version: version that will be downloaded.
asterisk_user: user that will be running asterisk
asterisk_user_password: user's password.
asterisk_fw_service: firewalld services that should be enabled.
asterisk_bin_url: Asterisk download URL
asterisk_bin_dir: Binaries directory
asterisk_dir_structure: Directorires that will be used by asterisk.

Example Playbook
----------------

Including an example of how to use your role (for instance, with variables passed in as parameters) is always nice for users too:

    - hosts: servers
      roles:
         - { role: preasterisk, asterisk_version: 18 }

License
-------

GPLv3

Author Information
------------------

Silvinux
