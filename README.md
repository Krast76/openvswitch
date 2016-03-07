Role Name
=========

OpenVSwitch deployment. Create also a standard bridge

Requirements
------------
None

Role Variables
--------------
- *krast_bridge_name*: Interface Name (Default "br0")
- *krast_bridge_ip*: Bridge IP (Default "172.16.76.1")
- *krast_bridge_netmask*: Bridge IP's Netmask (Default "255.255.255.0")

Dependencies
------------
None

Example Playbook
----------------

    - hosts: servers
      roles:
         - { role: openvswitch }

License
-------
BSD
