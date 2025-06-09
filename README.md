# 🏢 Small Office Network Design – Cisco Packet Tracer Project

## 📘 Project Overview

This project presents a **Small Office Network Design** built using **Cisco Packet Tracer**. It demonstrates fundamental concepts of **subnetting**, **VLAN implementation**, **inter-VLAN routing**, and **DHCP configuration**, tailored to a simulated office environment with three departments: **Admin**, **HR**, and **Customer**.

The purpose of this project is to showcase practical networking skills in designing a segmented and scalable office network, while ensuring efficient IP address allocation and logical network separation through VLANs.

---

## 🧠 Key Concepts Implemented

- **Subnetting** a /24 network into multiple /26 subnets using borrowed host bits
- Designing **logical VLANs** for department-level segmentation
- Setting up **inter-VLAN routing** using a router-on-a-stick method
- Configuring **DHCP services** to dynamically allocate IP addresses per subnet
- Assigning **host IPs and gateways** logically based on department structure
- Structuring the network with clarity and scalability in mind

---

## 🖧 Departmental VLAN Design

| Department  | VLAN ID | Subnet            | Host Range             | Default Gateway |
|-------------|---------|-------------------|-------------------------|-----------------|
| Admin       | 10      | 192.168.1.0/26    | 192.168.1.1 – .62       | 192.168.1.1     |
| HR          | 20      | 192.168.1.64/26   | 192.168.1.65 – .126     | 192.168.1.65    |
| Customer    | 30      | 192.168.1.128/26  | 192.168.1.129 – .190    | 192.168.1.129   |

---

## 🛠️ Tools & Technologies

- **Cisco Packet Tracer** (Simulation Tool)
- **IPv4 Subnetting**
- **VLANs and Trunking**
- **DHCP (Dynamic Host Configuration Protocol)**
- **Inter-VLAN Routing**

---

## 📂 Project Files

- `small-office-network.pkt` – Main Cisco Packet Tracer file
- `network-design.png` – Image of the network topology
- `Router Configurations.txt` – Pre-configured router commands
- `Switch configurations.txt` – Pre-configured switch commands
- `README.md` – Project documentation

---

## 🎯 Learning Objectives Achieved

- Designed a structured and segmented small office network
- Applied subnetting for efficient IP space utilization
- Separated departments logically using VLANs
- Implemented router-on-a-stick for communication between VLANs
- Enabled dynamic IP addressing through DHCP pools

