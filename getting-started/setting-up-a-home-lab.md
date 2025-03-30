# 🧪 Setting Up a Simple Home Cybersecurity Lab

A home lab is one of the best ways to build real skills and gain hands-on experience in cybersecurity. You can simulate attacks, practice defense, and explore tools—all in a safe, legal environment.

---

## 🧰 What You’ll Need

### 💻 A Computer with:
- At least **16GB of RAM** (8GB minimum)
- **100+ GB of free disk space**
- A CPU that supports virtualization (Intel VT-x or AMD-V)

### 🧱 Software:
- **Virtualization Platform**: VirtualBox (free) or VMware Workstation Player
- **ISO/VM Images**:
  - Kali Linux (for offensive tools)
  - Ubuntu or Windows 10 (target machines)
  - Security Onion or pfSense (optional for defensive labs)

---

## 🧪 Step-by-Step Lab Setup

### 1. Install VirtualBox or VMware
- Download from the official site and install.
- Enable virtualization in your BIOS/UEFI if needed.

### 2. Create Your VMs
- **Kali Linux** – For pen testing tools like Nmap, Burp Suite, and Metasploit.
- **Windows 10 VM** – Great for practicing privilege escalation and endpoint defense.
- **Ubuntu VM** – Use as a vulnerable target or for monitoring.
  
> Optional: Add **Metasploitable 2**, **DVWA**, or **Active Directory VMs** to simulate real-world networks.

### 3. Create an Internal Network
- Set all VMs to use “Host-Only” or “Internal” network mode.
- This ensures isolation from the internet while allowing VM-to-VM communication.

---

## 🔐 Lab Ideas to Try

| Goal | Practice |
|------|----------|
| Scanning | Use `nmap` to scan target VMs |
| Exploiting | Launch attacks with `Metasploit` |
| Web App Testing | Use DVWA or Juice Shop |
| Log Monitoring | Set up Security Onion and analyze logs |
| Defense | Harden a VM and test detection |

---

## 🌐 Online Lab Platforms (No Setup Needed)

- [TryHackMe](https://tryhackme.com) – Guided and beginner-friendly.
- [Hack The Box](https://hackthebox.com) – More advanced CTF-style labs.
- [RangeForce](https://rangeforce.com)
- [BlueTeamLabs](https://blueteamlabs.online)

---

## 🚀 Pro Tips

- Take notes on what you do and learn—build a lab journal.
- Record screen sessions for future review or portfolio use.
- Break things and fix them. That’s how you learn.

---

🏁 You're ready to dive in! From here, you can explore:
- [Core Concepts](../core-concepts/)
- [Attacks & Threats](../attacks-and-threats/)

Or return to the [Cybersecurity Knowledge Base Home](../README.md)
