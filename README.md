# Enterprise Network Engineering Lab

## Overview

An enterprise network engineering project focused on designing a secure, segmented, and scalable corporate network architecture.

## Network Architecture

The planned enterprise network uses separate VLANs for different organizational functions:

| VLAN | Purpose | Network |
|---|---|---|
| VLAN 10 | Engineering | 10.10.10.0/24 |
| VLAN 20 | Operations | 10.10.20.0/24 |
| VLAN 30 | Servers | 10.10.30.0/24 |
| VLAN 99 | Network Management | 10.10.99.0/24 |

## Networking Concepts

- VLAN segmentation
- 802.1Q trunking
- Inter-VLAN routing
- OSPF dynamic routing
- DHCP
- Access Control Lists (ACLs)
- SSH-based device management
- IP addressing and subnetting
- Network troubleshooting
- Network security

## Objectives

- Design a structured enterprise IP addressing plan
- Segment users and services using VLANs
- Enable controlled communication between network segments
- Implement dynamic routing
- Apply access-control policies
- Establish secure network management
- Validate connectivity and troubleshoot network failures

## Planned Validation

The network will be tested for:

- Same-VLAN connectivity
- Inter-VLAN connectivity
- DHCP address assignment
- Routing behavior
- ACL enforcement
- SSH management access
- Network failure and troubleshooting scenarios

## Tools

- Cisco Packet Tracer
- Cisco IOS networking concepts
- Git/GitHub