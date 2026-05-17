# Lab 04 - VLAN Segmentation & Inter-VLAN Routing

##  Objective
This lab demonstrates VLAN segmentation and inter-VLAN routing using a router-on-a-stick topology in Cisco Packet Tracer.

---

##  Network Topology

![Topology](screenshots/topology.png)

---

## VLAN Configuration
![VLAN](screenshots/vlan-brief.png)

| VLAN | Name   | Network         |
|------|--------|----------------|
| 10   | HR     | 192.168.10.0/24 |
| 20   | IT     | 192.168.20.0/24 |
| 30   | GUEST  | 192.168.30.0/24 |

---

##  IP Addressing Plan

### HR VLAN
- 192.168.10.11
- 192.168.10.12
- Gateway: 192.168.10.1

### IT VLAN
- 192.168.20.11
- 192.168.20.12
- Gateway: 192.168.20.1

### GUEST VLAN
- 192.168.30.11
- 192.168.30.12
- Gateway: 192.168.30.1

---

##  Configuration Summary
## Switch Config
![Switch Config](screenshots/vlan-config.png)

### Switch
- VLAN creation (10, 20, 30)
- Port assignment per VLAN
- Trunk configuration on Fa0/7

### Router
- Router-on-a-stick configuration
- Subinterfaces:
  - g0/0.10
  - g0/0.20
  - g0/0.30

---

##  Trunk Verification

![Trunk](screenshots/trunk.png)

---

##  Testing Results
## Testing

### HR ↔ IT
![Ping 1](screenshots/ping1.png)

### GUEST tests
![Ping 2](screenshots/ping2.png)

---

##  Key Learnings
- VLAN segmentation
- 802.1Q trunking
- Inter-VLAN routing (router-on-a-stick)
- Network isolation and controlled communication

---

##  Files Included
- Packet Tracer project (.pkt)
- Switch & Router configurations
- Screenshots of topology and tests
