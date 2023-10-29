---
title: Infrastructure
description: 
published: true
date: 2023-10-29T22:23:02.709Z
tags: 
editor: markdown
dateCreated: 2023-10-29T22:20:43.801Z
---

# Infrastructure
We currently have a small infrastructure but are planning to expand as per request of the orders that come in.

## HP DL160 GEN 9

### Hardware Inventory
 |Hardware | Description |
| ------------------- | -------------------------------|
| CPU | 2 x Intel Xeon E5-2603 V3 @ 1.60 GHz |
| RAM | 8 x 8Gb DIMM DDR4 ECC @ 2133 MHz |
| Storage 1 | 2 x 200Gb SSD in RAID 0 |
| Storage 2 | 2 x 1Tb SSD in RAID 0 |
| OS | HPE-ESXI-6.5.0-U3 Vsphere |
| Network | 2 x HP Ethernet 1Gb 2-port 361i Adapter |
| Network | HP NC375T PCIE Quad Port Gigabit Ethernet Adapter |

### VM List
1. PFSense Firewall
2. Windows Server 2016 DC
3. Web Node
4. Database Node
5. Game Node

### Network Listing
* Internal => Direct BBOX V3 Uplink
* ISP => PPPoe sessions in PFSense
* Clients 1
* Clients 2
* Clients 3
* Management Network => Access for Vsphere

### 