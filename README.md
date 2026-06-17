<img width="524" height="294" alt="image" src="https://github.com/user-attachments/assets/ba4e7ffa-dea0-4df7-8e7e-a1c826a7fea7" />
# 🏥 Hospital Network Design using Cisco Packet Tracer

A simulated enterprise-level hospital network built using Cisco Packet Tracer. The project demonstrates the design and implementation of a secure, scalable, and segmented network infrastructure for a modern hospital environment.

---

## 📖 Overview

This project models the network architecture of a hospital by dividing departments into separate networks using VLANs and implementing services such as DHCP, web servers, and secure communication between departments.

The goal of the project is to apply fundamental computer networking concepts in a real-world scenario while emphasizing security, manageability, and scalability.

---

## 🏗️ Network Architecture

The hospital network consists of the following departments:

* Reception / Administration
* Doctors Department
* Emergency Ward
* Intensive Care Unit (ICU)
* Laboratory
* Pharmacy
* Billing Department
* Server Room
* Guest WiFi Network

Each department is logically separated using VLANs to improve performance and security.

---

## 🚀 Features

* VLAN-based network segmentation
* Inter-VLAN communication
* Dynamic IP assignment using DHCP
* HTTP/Web Server configuration
* Secure port access using Port Security
* Password-protected network devices
* Remote device management (Telnet/SSH)
* Guest network isolation
* Structured IP addressing scheme
* End-to-end connectivity testing

---

## 🖥️ Technologies Used

* Cisco Packet Tracer
* Cisco Routers
* Cisco Switches
* DHCP Server
* Web Server
* VLANs
* Routing Protocols (RIP/Static Routing)
* Access Control Lists (ACLs)
* Port Security

---

## 🌐 Sample VLAN and IP Addressing Scheme

| VLAN | Department     | Network          |
| ---- | -------------- | ---------------- |
| 10   | Administration | 192.168.10.0/24  |
| 20   | Doctors        | 192.168.20.0/24  |
| 30   | ICU            | 192.168.30.0/24  |
| 40   | Laboratory     | 192.168.40.0/24  |
| 50   | Pharmacy       | 192.168.50.0/24  |
| 60   | Billing        | 192.168.60.0/24  |
| 100  | Server Room    | 192.168.100.0/24 |
| 200  | Guest WiFi     | 192.168.200.0/24 |

---

## 📂 Project Structure

```
Hospital-Network-Project/
│
├── Hospital_Network.pkt
├── Network_Diagram.png
├── Screenshots/
│   ├── Topology.png
│   ├── VLAN_Config.png
│   ├── DHCP_Config.png
│   └── Connectivity_Test.png
├── Report.pdf
└── README.md
```

---

## 🔧 Implemented Configurations

### VLAN Configuration

* Created separate VLANs for each department
* Configured trunk links between switches

### DHCP Configuration

* Automatic IP assignment for client devices
* Configured default gateway and DNS settings

### Routing

* Configured inter-VLAN routing
* Implemented RIP/static routing for network communication

### Security

* Console password protection
* Enable secret password
* Telnet/SSH configuration
* Port Security using sticky MAC addresses
* Guest network isolation

---

## 🧪 Testing Performed

* Verified IP assignment using DHCP
* Tested inter-department communication
* Verified server accessibility through HTTP
* Tested routing table entries
* Verified port security behavior
* Performed end-to-end ping tests

---

## 📸 Screenshots

Add screenshots of:

1. Complete Network Topology
2. VLAN Configuration
3. DHCP Configuration
4. Routing Table (`show ip route`)
5. Successful Ping Tests
6. Web Server Access

---

## 🎯 Learning Outcomes

Through this project, I gained practical experience with:

* Network Design Principles
* IP Addressing and Subnetting
* VLAN Configuration
* Routing and Switching
* DHCP Services
* Network Security Fundamentals
* Server Configuration
* Troubleshooting and Connectivity Testing

---

## 👨‍💻 Author

**Sufyan Malik**

Computer Networks Project – Hospital Network Design using Cisco Packet Tracer.
