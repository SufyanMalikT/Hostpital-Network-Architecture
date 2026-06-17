
# 🏥 Hospital Network Design using Cisco Packet Tracer

![Cisco Packet Tracer](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue)
![Project Type](https://img.shields.io/badge/Project-Hospital%20Network-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

<img width="521" height="287" alt="image" src="https://github.com/user-attachments/assets/2d83d4d3-665a-403d-8c47-da499fadb0a7" />

A simulated enterprise-level hospital network built using Cisco Packet Tracer. The project demonstrates the design and implementation of a secure, scalable, and segmented network infrastructure for a modern hospital environment.

---

## 📖 Overview

This project models the network architecture of a hospital by dividing departments into separate networks using VLANs and implementing services such as DHCP, web servers, and secure communication between departments.

The goal of the project is to apply fundamental computer networking concepts in a real-world scenario while emphasizing security, manageability, and scalability.

---

## 🏗️ Network Architecture

The hospital network consists of the following departments:

* Reception 
* Administration
* Doctors Department
* HR Department
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


---

## 🌐 Sample VLAN and IP Addressing Scheme

| VLAN | Department     | Network          |
| ---- | -------------- | ---------------- |
| 10   | Administration | 192.168.10.0/24  |
| 20   | HR Department  | 192.168.20.0/24  |
| 30   | Billing        | 192.168.30.0/24  |
| 40   | ICU            | 192.168.40.0/24  |
| 50   | Doctors        | 192.168.50.0/24  |
| 60   | Pharmacy       | 192.168.60.0/24  |
| 70   | Laboratory     | 192.168.70.0/24  |
| 80   | Reception      | 192.168.80.0/24  |
| 90   | Guest WiFi     | 192.168.90.0/24  |

---

## 📂 Project Structure

```
Hospital-Network-Project/
│
├── Hospital_Network.pkt
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

BS Computer Science 3rd Semester Computer Networks Project – Hospital Network Design using Cisco Packet Tracer.
