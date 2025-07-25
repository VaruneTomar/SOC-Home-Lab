<h1 align="center">🛡️ SOC Analyst Home Lab</h1>
<p align="center">
A fully virtualized detection lab simulating real-world cyberattacks to learn blue team defense, log analysis, and threat hunting using Splunk, Sysmon, Suricata, and the MITRE ATT&CK framework.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Status-In%20Progress-yellow" />
  <img src="https://img.shields.io/badge/SIEM-Splunk-blue" />
  <img src="https://img.shields.io/badge/EDR-Sysmon-blueviolet" />
  <img src="https://img.shields.io/badge/NIDS-Suricata-orange" />
  <img src="https://img.shields.io/badge/ATT&CK-MITRE-red" />
</p>

---

## 📌 Project Overview

This project is a home lab designed to demonstrate practical blue team cybersecurity skills for entry-level SOC Analyst roles. It simulates real-world attack techniques inside a safe, isolated virtual environment using:

- Endpoint logging (Windows + Sysmon)
- Network traffic analysis (Suricata)
- Centralized SIEM (Splunk)
- MITRE ATT&CK mapping for detection coverage

---

## 🔧 Lab Architecture

| Component          | OS              | Purpose                                      |
|--------------------|------------------|----------------------------------------------|
| 💻 SIEM Server     | Ubuntu Server    | Hosts Splunk Enterprise (Free Trial)         |
| 🪟 Target Endpoint | Windows 10/11    | Sysmon + Splunk Universal Forwarder          |
| 🧑‍💻 Attacker VM     | Kali Linux        | Attack simulation with Metasploit, etc.      |
| 🌐 NIDS VM         | Ubuntu Server    | Runs Suricata + Splunk Forwarder             |

> 🔒 All VMs are configured in **Host-Only Networking** for safe and controlled simulation.

---

## 🛠️ Technologies Used

- **Splunk Enterprise** (SIEM)
- **Splunk Universal Forwarder**
- **Sysmon** (Endpoint Visibility)
- **Suricata** (Network IDS)
- **MITRE ATT&CK Framework**
- **Kali Linux / Metasploit**
- **Windows Event Logs**
- **Custom Dashboards & Alerts**

---
