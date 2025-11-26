# 🛰 Network-Analyst-Team  
### Cybersecurity Lab Architect & Network Engineer  
Part of the TriadSec Virtualized Attack & Defense Lab

---

## ⭐️ Official Role Title  
Cybersecurity Lab Architect & Network Engineer

## 🎯 Role Summary  
The Network Analyst (Person A) is responsible for designing, deploying, and maintaining the complete virtual cybersecurity environment. This role ensures all systems are configured properly, communicate correctly, and are secured for simulated offensive operations.

This is the foundation of the entire TriadSec project.

---

## 🛠 Core Responsibilities

### 🔧 1. Virtual Machine Setup  
- Install and configure all required VMs:  
  - Kali Linux  
  - DVWA / Vulnerable Target Machine  
  - Monitor PC (Snort / Suricata / Security Onion)  
- Configure memory, CPU, adapters  

### 🌐 2. Network Architecture & Topology  
- Create Host-Only networks for controlled traffic  
- Configure Internal-only networks  
- Plan and document network layout  
- Assign static IPs for all nodes  
- Ensure attackers cannot reach the internet (local lab only)

### 📡 3. Connectivity & Routing  
- Ping tests  
- Route table verification  
- NAT configuration (if needed)  
- DNS and gateway validation  

### 🔒 4. Security & Hardening  
- Remove unnecessary services  
- Basic firewall rules  
- Ensure monitoring PC captures all traffic  

### 🧾 5. Documentation  
- Provide the team with:  
  - Final IP List  
  - Network Diagram  
  - VM Configuration File  
  - Connectivity Test Results  

---

## 📁 Repository Contents

The repository follows a clean, consistent structure to make collaboration and automation simple. All folder names use kebab-case and files are grouped by purpose.

```
network-analyst-team/
├── docs/
│   ├── topology-diagrams/        # Network diagrams (PNG, SVG, draw.io)
│   ├── setup-guides/             # Step-by-step VM & network setup guides
│   └── connectivity-reports/     # Final test reports and logs
├── configs/
│   ├── vm-configs/               # VirtualBox/VMX/OVF configs, Vagrantfiles
│   ├── network-configs/          # Host-only/internal network configs, DHCP
│   └── firewall-rules/           # Example iptables/ufw rules
├── scripts/
│   ├── provisioning/             # Scripts to provision VMs (bash/ansible)
│   └── test-scripts/             # ping/iptables/test automation scripts
├── tests/
│   ├── connectivity/             # ping, traceroute, route checks
│   └── monitoring-capture/       # tcpdump / tshark sample captures
├── .gitignore
├── CONTRIBUTING.md
├── SECURITY.md
├── README.md
└── ip-address-map.txt            # Final static IP assignment table
```

> Note: Put large VM images or ISO files in external storage (Google Drive/OneDrive) and reference download links in docs/setup-guides/ rather than committing large binaries to the repo.

---

## 🧠 What This Role Demonstrates  
✔️ Strong foundational networking knowledge  
✔️ Ability to build full security labs  
✔️ DevSecOps-style environment deployment  
✔️ Understanding of OSI layers, routing, and interfaces  
✔️ System administration & virtualization skills  

Perfect for roles like:  
- Junior Network Engineer  
- SOC Technician  
- DevSecOps Intern  
- Cybersecurity Lab Engineer  

---

## 🏆 Contribution to TriadSec  
Every attack and vulnerability test relies on your network setup.  
Your work ensures the entire team operates on:  
- A stable  
- Secure  
- Repeatable  
- Realistic  
cybersecurity simulation environment.

---
