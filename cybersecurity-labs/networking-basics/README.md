# 🌐 Lab 00: Core Networking Foundations & Packet Mechanics

Before deploying defensive rules or launching reconnaissance scans, a security analyst must understand how information traverses boundaries. This lab explores the architectural models and packet parsing flows running on your Linux Mint host.

---

## 🏗️ The OSI Model Reference Framework

When troubleshooting or intercepting network data, map your tools and vectors to the corresponding OSI layers:

| Layer Number | OSI Layer Name | Primary Protocol Units | Security / Auditing Context |
| :--- | :--- | :--- | :--- |
| **Layer 7** | Application | HTTP, FTP, SSH, DNS | Web Application Firewalls (WAF), Payload Inspection |
| **Layer 4** | Transport | TCP, UDP | Port Auditing, Firewall Filter States, SYN Flags |
| **Layer 3** | Network | IP, ICMP | Router Tables, IP Routing Bounds, Ping Sweeps |
| **Layer 2** | Data Link | MAC Addresses, ARP | Switch VLAN Isolation, ARP Spoofing Mitigation |

---

## 🚏 Local Routing Tables Exploration

To inspect how your local operating system routes packets through active interfaces, execute this native terminal command:
```bash
ip route show
