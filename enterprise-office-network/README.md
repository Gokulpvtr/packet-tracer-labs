# 🏢 Enterprise Office Network Design

## Overview

Designed and implemented an enterprise office network using Cisco Packet Tracer.

The network is divided into three departments:

- IT Department (VLAN 10)
- HR Department (VLAN 20)
- Finance Department (VLAN 30)

Inter-VLAN communication is enabled using Router-on-a-Stick architecture.

---

## Network Topology

### Devices Used

| Device | Quantity |
|----------|----------|
| Cisco 1941 Router | 1 |
| Cisco 2960 Switch | 2 |
| PCs | 9 |

---

## VLAN Configuration

| VLAN | Department | Network |
|--------|------------|----------|
| 10 | IT | 192.168.10.0/24 |
| 20 | HR | 192.168.20.0/24 |
| 30 | Finance | 192.168.30.0/24 |

---

## Features Implemented

- VLAN Segmentation
- Router-on-a-Stick
- DHCP Configuration
- Inter-VLAN Routing
- Network Testing using Ping
- Enterprise Network Design

---

## Skills Learned

- VLAN Creation
- Switch Configuration
- Router Configuration
- DHCP Pools
- Trunk Ports
- Inter-VLAN Routing
- Network Troubleshooting

---

## Screenshots

### Network Topology

![Topology](topology.png)

### VLAN Configuration

![VLAN](vlan-config.png)

### DHCP Configuration

![DHCP](dhcp-config.png)

### Connectivity Testing

![Ping](ping-test.png)

---

## Results

Successfully configured:

- VLAN 10 (IT)
- VLAN 20 (HR)
- VLAN 30 (Finance)

All departments received IP addresses automatically through DHCP and communicated successfully through inter-VLAN routing.

---

## Tools Used

- Cisco Packet Tracer
- Cisco IOS CLI

---

## Author

**Gokulkrishnan S**

BCA Student | Networking & Cybersecurity Enthusiast
