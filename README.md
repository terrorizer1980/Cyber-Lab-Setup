# Cyber-Lab-Setup
I set up a testing environment using multiple small Netgear routers, two Windows 10 PC workstations, a dual-bootable laptop with Windows 10 and Kali Linux, a Cisco managed switch, a server running Windows Server 2019, and a Raspberry Pi configured to simulate a WAN.

Configuration:
+---------+             +---------+
| Pentest |             | Pentest |
|         |-------------|         |
|   PC    |             |  Router |
+---------+             +---------+
192.168.1.2      192.168.1.1    10.2.50.16
