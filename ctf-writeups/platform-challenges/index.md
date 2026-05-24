# 📝 Challenge Write-up Template & Log Reference

**Challenge Name:** `[e.g., Basic-Pentesting-01]`  
**Platform Source:** `[e.g., TryHackMe / Local Lab]`  
**Track Focus:** `[Network Recon / Web Exploitation / Privilege Escalation]`  
**Difficulty Baseline:** `[Easy / Medium / Hard]`

---

## 🔍 Stage 1: Target Fingerprinting
We initiated target tracking by executing a standard stealth SYN port scan to map active services:
```bash
sudo nmap -sS -sV -O <TARGET_IP>
