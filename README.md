# University Campus Network — Cisco Packet Tracer

A university campus network designed and implemented in **Cisco Packet Tracer** for ITCS372.

The project simulates a multi-building campus with centralized services, dynamic routing, network segmentation, security policies, VoIP, wireless networking, Internet connectivity, and redundancy.

A separate troubleshooting activity is included with intentionally introduced configuration faults for users to diagnose and repair.

## Network Features

- Multi-building campus network
- VLAN and subnet segmentation
- Inter-VLAN routing
- OSPF dynamic routing
- Centralized DHCP with DHCP relay
- DNS and internal web services
- ACL-based network security
- Wireless networks
- Cisco IP phones and Voice VLANs
- NAT/PAT Internet access
- Redundant Internet edge routing
- Syslog and NTP services

## Files

| File | Description |
|---|---|
| `AdminProj_work_final.pkt` | Fully configured and working campus network |
| `AdminProj_poison.pkt` | Network containing intentional configuration faults |
| `Admin-Project-Activities.pka` | Packet Tracer troubleshooting activity with instructions, hints, and automatic assessment |

## Troubleshooting Activity

The `.pka` activity contains **9 troubleshooting incidents** covering different areas of the network:

1. ICT Staff VLAN misconfiguration
2. Engineering DHCP relay failure
3. Science Voice VLAN failure
4. Business DNS/ACL failure
5. Administration Wi-Fi trunk failure
6. Library OSPF routing failure
7. Dormitory B DHCP relay failure
8. Backup Internet routing failure
9. Data Center management ACL failure

Students are given symptoms rather than the location of each fault and must use Cisco IOS troubleshooting commands to diagnose and repair the network.

The activity includes a network reference, addressing information, troubleshooting tickets, optional hints, detailed solution hints, and Packet Tracer **Check Results** assessment items.

## How to Use

### Explore the Working Network

Open:

`AdminProj_work_final.pkt`

Use this file to inspect the complete working campus topology and configurations.

### Troubleshoot Without Assessment

Open:

`AdminProj_poison.pkt`

This contains the same campus network with the intentional faults already introduced.

### Run the Troubleshooting Lab

Open:

`Admin-Project-Activities.pka`

Follow the included tickets, troubleshoot the network, repair the configurations, and use **Check Results** to evaluate your work.

## Tools

- Cisco Packet Tracer
- Cisco IOS CLI
- Packet Tracer Activity Wizard

## Project Goal

The goal of this project is to provide a realistic university campus network where networking concepts can be applied together and where configuration problems can be diagnosed through practical troubleshooting rather than predefined configuration steps.

## Disclaimer

This network is a simulated academic environment created in Cisco Packet Tracer. IP addresses, services, organizations, and network infrastructure shown in the project are part of the simulation.
