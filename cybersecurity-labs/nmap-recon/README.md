# 🔍 Lab 01: Host Discovery and Port Auditing with Nmap
# Date : 24 may 2026

Welcome to the Network Reconnaissance sandbox module for **NexusCore-SLIATE**. 

Before starting any security evaluation or defensive profiling, an analyst must gain network visibility. This lab guides you through using Network Mapper (`nmap`) on your local machine to discover active nodes, identify structural port vulnerabilities, and map service fingerprints cleanly without destabilizing network environments.

---

## 🛑 Strict Scope Boundaries (The Golden Directive)

To ensure full ethical and legal compliance under the NexusCore organization code of conduct, your execution boundaries are strictly limited to your authorized local machine subnets.

* 🌌 **Permitted Targets:** `127.0.0.1`, `192.168.1.0/24` (or your isolated virtual machine interface subnet).
* 🚫 **Forbidden Targets:** Do not scan institutional campus network routes, public web interfaces, or external student systems.

---

## 🛠️ Phase 1: Local Network Interface Identification

Before firing scanning packets, map out your active hardware interfaces and gateway boundaries on your **Linux Mint** console terminal.

```bash
# Display all operational network connections and IP blocks
ip address show``` 
