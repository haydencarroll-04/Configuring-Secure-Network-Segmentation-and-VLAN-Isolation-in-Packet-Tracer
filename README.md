# Configuring-Secure-Network-Segmentation-and-VLAN-Isolation-in-Packet-Tracer
Cisco Packet Tracer project demonstrating secure network segmentation and VLAN isolation for DHCP and web server networks.

# Configuring Secure Network Segmentation and VLAN Isolation in Cisco Packet Tracer

This project demonstrates how to design and implement a segmented network infrastructure using Cisco Packet Tracer, featuring:

- Dynamic IP allocation via **DHCP**
- VLAN isolation for dedicated **web servers**
- Secure, segmented inter-network communication

---

## Tools Used
- Cisco Packet Tracer
- Subnet Calculator ([calculator.net/ip-subnet-calculator](https://www.calculator.net/ip-subnet-calculator.html))

---

## Project Overview

This lab simulates a corporate network with:
- A 14-node DHCP-enabled subnet
- A 6-node VLAN-isolated subnet hosting two web servers
- Router-based interconnection between the two segments

The setup improves both security and network management efficiency

---

## Network Design

| Component | Description |
|------------|-------------|
| Router | Cisco 2621XM |
| Switches | Two 2960-24TT |
| PCs | 20 (14 + 6) end devices |
| Servers | Two web servers (VLAN isolated) |
| DHCP | Configured with dynamic IP pool for 14-node network |

---

## Configuration Highlights
- VLAN 10 created for Web Server R&D
- Router interfaces configured for inter-VLAN routing
- DHCP server providing dynamic IP allocation
- Connectivity verified with ping and tracert commands

---

## Testing & Validation
- VLAN isolation confirmed (cross-VLAN pings blocked)  
- Inter-network connectivity established via router  
- Dynamic IP assignment functioning for all 14 DHCP nodes

