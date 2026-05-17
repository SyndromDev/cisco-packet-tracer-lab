# Lab 3 - DHCP Network Configuration

## Objective
Configure a router as a DHCP server to automatically assign IP addresses to devices in two different LAN networks.

---

## Technologies Used
- Cisco Packet Tracer
- DHCP
- IPv4
- Router
- Switch
- ICMP (Ping)

---

## Network Topology

![Topology](lab3-dhcp-network/screenshots/topology.png) 

*Figure 1: Network topology with router-based DHCP configuration*

---

## Router DHCP Configuration

![Router DHCP](lab3-dhcp-network/screenshots/router-dhcpconfig.png)

*Figure 2: DHCP pools configured on the router for both LAN networks*

---

## PC0 DHCP Configuration

![PC0 DHCP](lab3-dhcp-network/screenshots/dhcp-configpc0.png) 

*Figure 3: PC0 automatically receiving IP configuration from DHCP server*

---

## PC1 DHCP Configuration

![PC1 DHCP](lab3-dhcp-network/screenshots/dhcp-configpc1.png) 

*Figure 4: PC1 automatically receiving IP configuration from DHCP server*

---

## Connectivity Test

![Ping Test](lab3-dhcp-network/screenshots/ping.png)

*Figure 5: Successful ICMP communication between hosts in different networks*

---

## Result
- Router configured as DHCP server
- Automatic IP address assignment working correctly
- Inter-network communication successful
- DHCP pools successfully distribute gateway and network settings

---

## Skills Demonstrated
- DHCP configuration
- Router interface configuration
- IPv4 addressing
- Network troubleshooting
- Inter-network routing
- Cisco IOS CLI
