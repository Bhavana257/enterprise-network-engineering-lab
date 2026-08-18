\# Network Design



\## Objective



Design a secure and segmented enterprise network supporting Engineering, Operations, Server, and Network Management environments.



\## VLAN Plan



| VLAN | Department | Network | Purpose |

|---|---|---|---|

| 10 | Engineering | 10.10.10.0/24 | Engineering users |

| 20 | Operations | 10.10.20.0/24 | Operations users |

| 30 | Servers | 10.10.30.0/24 | Internal services |

| 99 | Management | 10.10.99.0/24 | Network device management |



\## Routing



Inter-VLAN routing will provide controlled communication between VLANs.



OSPF is planned for dynamic routing between enterprise network segments/sites.



\## Network Security



ACL policies will be used to restrict unauthorized communication between departments and protect server resources.



SSH will be used for secure network-device administration.



\## Network Services



\- DHCP for automated IP address assignment

\- DNS for hostname resolution

\- SSH for secure management



\## Troubleshooting Scenarios



The lab will validate common network failures including:



\- Incorrect VLAN assignment

\- Trunk configuration problems

\- Routing failures

\- DHCP failures

\- ACL blocking required traffic

\- Connectivity between network segments

