\# IP Addressing Plan



| VLAN | Purpose | Network | Default Gateway |

|---|---|---|---|

| VLAN 10 | Engineering | 10.10.10.0/24 | 10.10.10.1 |

| VLAN 20 | Operations | 10.10.20.0/24 | 10.10.20.1 |

| VLAN 30 | Servers | 10.10.30.0/24 | 10.10.30.1 |

| VLAN 99 | Management | 10.10.99.0/24 | 10.10.99.1 |



\## Addressing Strategy



\- `/24` subnets are used for clear departmental segmentation.

\- `.1` is reserved as the default gateway for each VLAN.

\- The Management VLAN is separated from user and server traffic.

\- DHCP can be used for end-user devices.

\- Servers and network infrastructure can use reserved/static addresses.



\## Planned Network Services



\- DHCP

\- DNS

\- Inter-VLAN Routing

\- OSPF

\- ACL-based traffic control

\- SSH management

