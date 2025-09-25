# 🔐 Secure Research Lab Infrastructure

This project demonstrates the design and implementation of a **segmented, security-hardened enterprise-style research lab network** using **Cisco Packet Tracer**.

##  Project Overview
The network simulates a secure environment for **Researchers, Students, Admins, Servers (DMZ), and Wi-Fi zones**, with multiple security layers:
- VLAN Segmentation
- ACL-based firewalling
- SSH-only administrative access
- WPA2-AES wireless security + MAC filtering
- DMZ firewall simulation
- ISP/Cloud connectivity
- Routing with RIP + OSPF coexistence

## 🖥️ Topology & Devices
- **12 PCs, 2 Laptops, 3 Servers**
- **2 Switches, 1 Cisco Router**
- **1 Wireless Router, 1 ISP Cloud**

## 📂 Repository Structure

##  VLAN Design
| VLAN ID | Department    | IP Range          |
|---------|--------------|------------------|
| 10      | Researchers  | 192.168.10.0/24  |
| 20      | Students     | 192.168.20.0/24  |
| 30      | Admin        | 192.168.30.0/24  |
| 40      | Servers (DMZ)| 192.168.40.0/24  |
| 50      | Wi-Fi Zone   | 192.168.50.0/24  |

## 🛡️ Security Features
- 🔹 **Segmentation** → 5 VLANs isolating roles  
- 🔹 **ACLs** → Researchers limited to servers, Students blocked from SSH/HTTP  
- 🔹 **SSH-only Admin Access** → Secure remote management  
- 🔹 **Wireless Protection** → WPA2-AES + MAC filtering  
- 🔹 **DMZ Simulation** → Servers isolated with firewall rules  
- 🔹 **Routing** → Router-on-a-Stick with RIP & OSPF coexistence  
- 🔹 **ISP Simulation** → Default route to Cloud ISP  

##  Testing & Validation
- Students blocked from researcher resources  
- Admin access via SSH only  
- Unauthorized MACs rejected from Wi-Fi  
- DMZ servers isolated properly  
- ACLs enforced successfully  
- Inter-VLAN routing functional  

**Tests performed:** Ping, SSH sessions, Wi-Fi association, ACL deny checks, server reachability

##  Documentation
The full **Project Report (PDF)** is included in [`/report`](./report).

## ⚙️ Tools & Technologies
- **Cisco Packet Tracer**
- **VLANs**
- **ACLs**
- **SSH**
- **RIP / OSPF**
- **DMZ**
- **WPA2 Wireless Security**

## 👤 Author
**Agha Essa Khan**  
 Date: July 20, 2025  

---
⭐ If you find this project useful, don’t forget to star the repo!
