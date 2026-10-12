# Cisco Packet Tracer Portfolio

This repository contains my hands-on computer networking labs and configuration files.

---

## Lab 1: Small Office DHCP Configuration
![Lab 1 Network Topology](lab1_topology.png)
### Project Objective
Demonstrates how to configure a Cisco router as a DHCP server to automatically assign IP addresses to end devices within a local area network (LAN).

### Network Topology & Settings
- **Router:** Cisco 4331 (Default Gateway: 192.168.1.1)
- **Switch:** Cisco 2960
- **Hosts:** 2 PCs configured for DHCP

---

## Lab 2: Secure Home Wi-Fi Network
![Lab 2 Network Topology](lab2_topology.png)
### Project Objective
Demonstrates how to set up a wireless home network, customize the network name (SSID), and deploy WPA2 Personal password security to encrypt the network links.

### Network Topology & Settings
- **Wireless Router:** Linksys WRT300N
- **SSID (Network Name):** MyHomeWifi
- **Security Type:** WPA2 Personal (AES Encryption)
- **Hosts:** 1 Wireless Laptop (WPC300N module swap), 1 Smartphone

---

## Lab 3: Multi-Router Inter-Department Static Routing
![Lab 3 Network Topology](lab3_topology.png)
### Project Objective
Demonstrates how to interconnect separate office corporate departments across a dual-router backbone layout using manual static routes for reliable end-to-end delivery.

### Network Topology & Settings
- **Sales Infrastructure:** Router-Sales (Gateway: 192.168.10.1) -> Switch -> PC0 Static IP (192.168.10.10)
- **HR Infrastructure:** Router-HR (Gateway: 192.168.20.1) -> Switch -> PC1 Static IP (192.168.20.10)
- **Backbone Link:** Serial/Copper connection between routers on the 10.0.0.0/30 transit network block.
- **Routing Logic:** Configured `ip route` tables on both endpoints for cross-department ping confirmation.

---

## How to Run These Labs
1. Download and install [Cisco Packet Tracer](https://netacad.com).
2. Download the `.pkt` files from this repository.
3. Open the files in Packet Tracer to view the active topologies and running configurations.
