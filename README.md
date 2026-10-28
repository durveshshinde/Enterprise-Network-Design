# Enterprise Network Design Using Cisco Packet Tracer

## 📌 Project Overview
This project demonstrates the design and configuration of an enterprise network using Cisco Packet Tracer. It focuses on routing, switching, IP addressing, and network connectivity verification using Cisco IOS command-line tools.

## 🎯 Objectives
- Design an enterprise network topology.
- Configure router interfaces and IP addresses.
- Implement OSPF dynamic routing.
- Verify routing tables and network connectivity.
- Inspect switch interfaces and MAC address tables.
- Practice network troubleshooting using Cisco IOS commands.

## 🛠️ Technologies Used
- Cisco Packet Tracer
- Cisco IOS CLI
- OSPF (Open Shortest Path First)
- IPv4 Addressing
- Routing and Switching
- Network Troubleshooting

## ⚙️ Key Configurations

### 1. Router Interface Verification
Command:
```text
show ip interface brief
```
Used to verify interface IP addresses and operational status.

### 2. OSPF Routing Verification
Command:
```text
show ip route
```
OSPF-learned routes are identified by the letter `O` in the routing table.

### 3. Connectivity Testing
Commands:
```text
ping 192.168.20.1
ping 192.168.30.1
```
Both connectivity tests returned a **100% success rate (5/5 packets)** during testing.

### 4. Switch MAC Address Table
Command:
```text
show mac address-table
```
Used to inspect dynamically learned MAC addresses and the switch ports associated with them.

## 📸 Project Screenshots

Screenshots are available in the `screenshots/` folder.

### Network Topology
![Network Topology](screenshots/01-network-topology.png)

### OSPF Routing Table
![OSPF Routing Table](screenshots/02-ospf-routing-table.png)

### Connectivity Tests
![Connectivity
