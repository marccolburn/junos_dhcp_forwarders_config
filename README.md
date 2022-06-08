DHCP Forwarding Configuration
=========

Configure DHCP Forwarding for Junos.

Requirements
------------


Role Variables
--------------
dhcp_forwarders: List of Dictionaries containing DHCP Forwardings



Dependencies
------------

N/A

Example Playbook
----------------

    - hosts: all
      roles:
         - { role: junos_dhcp_forwarders_config }

License
-------

BSD

Author Information
------------------

Marc Colburn Juniper
