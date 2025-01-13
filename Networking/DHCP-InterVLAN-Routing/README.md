# DHCP Server on Router Plus + Inter-VLAN Routing

## Overview
This project demonstrates the configuration of a **DHCP server on a router** to dynamically assign IP addresses to devices across multiple VLANs, along with the implementation of **Inter-VLAN Routing** to enable communication between them.

## Topology
- **Devices Used:**
  - 1 Router
  - 1 Switch
  - 6 PCs (2 assigned to each VLAN)

## Project Steps
### Step 1: VLAN Configuration on the Switch
- Created VLANs and assigned them to their respective switch ports.

### Step 2: Sub-Interface Configuration on the Router
- Configured sub-interfaces on the router for each VLAN.
- Assigned unique IP addresses to each sub-interface to act as the default gateway for the respective VLAN.

### Step 3: DHCP Configuration on the Router
- Created DHCP pools for each VLAN.
- Configured IP ranges, default gateways, and subnet masks to dynamically allocate IP addresses to devices in each VLAN.

## Challenges Faced
- Devices initially failed to receive the correct default gateway via DHCP.
- Issue resolved by ensuring adequate time for DHCP services to assign IP addresses properly.

## Learning Outcomes
- Deepened understanding of VLANs, Inter-VLAN Routing, and DHCP.
- Gained hands-on experience in troubleshooting DHCP and routing configurations.
## Files Included
## Files Included
- **Packet Tracer File:** [Download Here](Networking/DHCP-InterVLAN-Routing/PacketTracerFiles)

