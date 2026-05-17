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

![Topology](screenshots/topology.png)


*Figure 1: Network topology with router-based DHCP configuration*

---

## Router DHCP Configuration

![Router Config](screenshots/router-config.png)


*Figure 2: DHCP pools configured on the router for both LAN networks*

---

## PC0 DHCP Configuration

![PC0](screenshots/pc0-ip.png)


*Figure 3: PC0 automatically receiving IP configuration from DHCP server*

---

## PC1 DHCP Configuration

![PC1](screenshots/pc1-ip.png)


*Figure 4: PC1 automatically receiving IP configuration from DHCP server*

---

## Connectivity Test

![Ping](screenshots/ping-test.png)


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
