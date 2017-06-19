windows_time
=========

This role can be used for enable and configure windows time.
Creates scheduled task to sync time every hour.

Requirements
------------

This role requires Ansible 1.2 or higher, and platform requirements are listed in the metadata file.

Role Variables
--------------

time_zone: "Russian Standard Time"
ntp_server: time.windows.com

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: windows_time, time_zone: "Russian Standard Time", ntp_server: time.windows.com  }

License
-------

MIT

Author Information
------------------

Aleksey Demidov