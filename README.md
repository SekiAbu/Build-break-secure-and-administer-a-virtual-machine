# Build → Break → Secure → Administer Virtual Machine Project

This repository documents a full lifecycle security engineering project where I:
1. **Built** a Linux Mint virtual machine from the ground up  
2. **Broke** it intentionally through misconfigurations and controlled attacks  
3. **Secured** and hardened the system using defensive best practices  
4. **Administered** it like a production environment with monitoring, logging, and maintenance

The project demonstrates adversarial thinking, system hardening, protocol analysis, and hands-on Linux administration.

---

## 🚀 Project Goals

- Create a reproducible, end-to-end cybersecurity lab environment  
- Practice offensive and defensive techniques in a controlled VM  
- Strengthen troubleshooting, documentation, and system design skills  
- Build a portfolio artifact showcasing real-world security engineering


---

## 🛠️ Technologies Used

- **Linux Mint** (VM host OS)
- ** Oracle virtual Box
- **OpenSSH
- **Wireshark
- **UFW 
- **Fail2ban
- **Python

---

## 🧩 Phase Breakdown

### 🔨 1. Build Phase
- VM provisioning  
- Network configuration (static IP, DNS, routing)  
- SSH setup  
- Baseline system state documentation  
  

### 💥 2. Break Phase
- Threat modeling  
- Intentional misconfigurations  
- Attack simulations (port scanning, brute force, service abuse)  
- Packet captures and protocol analysis  
- Exploit attempts and outcomes  

### 🔐 3. Secure Phase
- Hardening SSH, firewall, permissions  
- Service lockdown  
- IDS/IPS configuration  
- Remediation and verification  
- Before/after comparisons  

### 🛠️ 4. Administer Phase
- Monitoring scripts  
- Log rotation  
- Patch management  
- Backup strategy  
- Audit reports  

---

## 🔁 Reproduction Guide

A step-by-step guide for anyone who wants to recreate the environment:

1. Clone the repository  
2. Follow the build steps.md instructions to set up the VM  
3. Apply the break steps.md  misconfigurations or attacks  
4. Implement the securing phase steps. md hardening steps  
5. Use the administering phase step.md  to maintain the system  

---

## 📸 Screenshots 

All visual documentation is stored in the `docs/` directory:
- This contains a power point presentation on the project with screenshots of each phase.
- VM architecture  
- Before/after security states  
- Attack and defense screenshots  

---

## 📄 License

MIT License 

---

## 🙌 Acknowledgments

This project is inspired by real-world security engineering workflows and academic lab methodologies.


