# Lab 05 - ACL Security Between VLANs

#  Objective
This lab demonstrates VLAN segmentation and traffic filtering using Access Control Lists (ACLs) in Cisco Packet Tracer.

---

##  Network Topology

![Topology](screenshots/topology.png)

---

##  VLAN Configuration

![VLAN](screenshots/vlan.png)

---

##  Trunk Configuration

![Trunk](screenshots/trunk.png)

---

##  ACL Configuration

![ACL](screenshots/acl-config.png)

---

##  Router Configuration

![Router Config](screenshots/router-config.png)

---
##  Traffic Policy

| Source VLAN | Destination VLAN | Action |
|---|---|---|
| GUEST | HR | Denied |
| GUEST | IT | Denied |
| HR | IT | Allowed |
| IT | HR | Allowed |


##  Testing Results

### ✔ Allowed Traffic
HR ↔ IT communication works successfully.

![Allowed Traffic](screenshots/ping-hr-it.png)

---

###  Blocked Traffic
GUEST VLAN is blocked from accessing HR and IT VLANs.

![Blocked Traffic](screenshots/ping-guest-blocked.png)

---

##  Key Learnings
- VLAN segmentation
- 802.1Q trunking
- Router-on-a-stick routing
- Network security fundamentals

##  Technologies Used

- Cisco Packet Tracer
- VLANs
- 802.1Q Trunking
- Extended ACLs
- Router-on-a-Stick
