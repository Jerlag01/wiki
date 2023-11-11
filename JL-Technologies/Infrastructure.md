---
title: Infrastructure
description: 
published: true
date: 2023-11-11T17:07:19.440Z
tags: 
editor: markdown
dateCreated: 2023-10-29T22:20:43.801Z
---

# Infrastructure
We currently have a small infrastructure but are planning to expand as per request of the orders that come in.

## HP DL380 SFF GEN 9

### Hardware Inventory
 |Hardware | Description |
| ------------------- | -------------------------------|
| CPU | 2 x Intel Xeon E5-2680 V3 @ 2.50 GHz |
| RAM | 12 x 16Gb DIMM DDR4 ECC @ 2133 MHz |
| Storage 1 | 6 x 200Gb SSD in RAID 5 |
| Storage 2 | 2 x 1Tb SSD in RAID 0 |
| Storage 3 | 2 x 1Tb SSD in RAID 0|
| OS | HPE-ESXI-6.5.0-U3 Vsphere |
| Network ILO | 1 x HP Ethernet 1Gb 2-port 361i Adapter |
| Network |  HP 331FLR 4x 1GBE RJ45 Quad port Nic |

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