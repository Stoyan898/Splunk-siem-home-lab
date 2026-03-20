# 🛡️ Splunk SIEM Home Lab

[![VirtualBox](https://img.shields.io/badge/VirtualBox-Oracle-blue)](https://www.virtualbox.org/) 
[![Splunk](https://img.shields.io/badge/Splunk-SIEM-orange)](https://www.splunk.com/)
[![CompTIA Security+](https://img.shields.io/badge/Certified-CompTIA%20Security%2B-green)](https://www.comptia.org/certifications/security)

## 📋 Project Overview

After earning my **CompTIA Security+** certification with **zero professional experience**, I built this complete hands-on home lab to gain real-world skills in **SIEM (Security Information and Event Management)** using Splunk — one of the most in-demand tools in cybersecurity.

My goal: climb the cyber security ladder starting from entry-level SOC roles. This lab proves I’m a **motivated, quick learner** who doesn’t wait for experience — I create it.

## 🖥️ Lab Architecture

### Virtual Machines (Oracle VirtualBox)
- **ubuntu** — Base Ubuntu Linux VM (cloned for multiple instances)
- **Splunkfwd** — Splunk Universal Forwarder (Linux-based log collector)
- **splunkWindows** — Windows 11 VM running Splunk Enterprise (main indexer & search head)

**Key Specs** (all VMs):
- 8 GB RAM, 2 CPUs
- Bridged networking (realistic traffic)
- PuTTY for secure SSH remote access to Linux VMs

### Technologies Used
- Hypervisor: Oracle VirtualBox
- OS: Ubuntu Linux + Windows 11
- SIEM: Splunk Enterprise + Universal Forwarder
- Remote Access: PuTTY (SSH)
- Storage: 50 GB (Ubuntu) + 100 GB (Windows)

## 📸 Screenshots
*(Add your 4 screenshots here after uploading them)*

![VirtualBox Manager](screenshot-1.png)  
*VirtualBox Manager showing all three VMs*

![Ubuntu Details](screenshot-2.png)  
*Ubuntu VM configuration*

![splunkWindows Details](screenshot-3.png)  
*Windows 11 VM with Splunk*

![Running Lab with PuTTY](screenshot-4.png)  
*Ubuntu running via PuTTY + splunkWindows desktop*

## 🚀 How I Built It (Step-by-Step)

1. Installed Oracle VirtualBox
2. Downloaded Ubuntu ISO → Created base Linux VM → Cloned it to make `Splunkfwd`
3. Downloaded PuTTY for remote SSH access
4. Downloaded Windows 11 ISO → Created `splunkWindows` VM
5. Installed and configured Splunk Enterprise (Windows) + Universal Forwarder (Linux)

## 🎯 What I’m Learning & Next Steps
- Log ingestion, parsing, and indexing
- Creating dashboards and detection alerts
- Simulating attacks and practicing incident response
- Expanding with more data sources and tools (Wazuh, Elastic, etc.)

**Current Status**: Lab is fully running and ready for daily experimentation.

---

**"No experience? Build it yourself."**  
This project shows my initiative, dedication, and fast-learning ability. I’m actively looking for my first role in cybersecurity (SOC Analyst, Security Operations, Junior SIEM Analyst). Always open to advice, mentorship, or opportunities!

Made with motivation • March 2026
