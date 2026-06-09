<div align="center">

# 🔎 MailScope Enterprise

**Advanced Email Investigation & Forensics Platform** <br/>
*Engineered for SOC Analysts & DFIR Teams*

<br/>

[![Live Demo](https://img.shields.io/badge/Launch_Platform-Visit_Now-4f46e5?style=for-the-badge)](https://mahmoudnazmy.github.io/MailScope/)
[![Framework](https://img.shields.io/badge/Vue_3-42b883?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org)
[![Language](https://img.shields.io/badge/TypeScript_5-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-0ea5e9?style=for-the-badge)](LICENSE)

</div>

<br/>

## ▌ Platform Overview

**MailScope** is a client-side, open-source email investigation platform designed to assist **Security Operations Center (SOC)** analysts, **Digital Forensics and Incident Response (DFIR)** practitioners, and cybersecurity researchers in conducting deep, structured email investigations — directly in the browser.

> [![Privacy First](https://img.shields.io/badge/Privacy_First-Zero_Backend_&_No_Data_Transmission-10b981?style=flat-square)](#)  
> All processing happens locally on your device. No email content is ever sent to a server.

<br/>

## ▌ Core Intelligence Modules

### 1. Header Analysis
Deep-dive into raw internet message headers with full forensic reconstruction.
- **SMTP Relay Chain** mapping and timing analysis
- **SPF, DKIM, DMARC, ARC** cryptographic verification
- **Header spoofing** and path mismatch detection
- **Automated IOC extraction** (IPs, Domains, Addresses)

### 2. Body Analysis
Forensic inspection of email body content for malicious intent signals.
- **Malicious URL** scanning and redirect chain tracking
- **Brand impersonation** and phishing pattern detection
- **HTML payload deobfuscation** (Base64, hex encoding)
- **Social engineering** language and urgency analysis

### 3. Full Email Forensics
Unified correlated analysis combining header and body forensics in a single report.
- **.EML / .MSG** parsing and processing
- **Unified threat scoring** (Critical → Low)
- **MIME tree hierarchy** viewer for multipart messages
- **High-fidelity reporting** for incident documentation

<br/>

## ▌ Investigation Workflow

<div align="center">

[![Select Module](https://img.shields.io/badge/1.-Select_Module-6366f1?style=for-the-badge)](#) ➔
[![Input Data](https://img.shields.io/badge/2.-Input_Data-8b5cf6?style=for-the-badge)](#) ➔
[![Analyze Results](https://img.shields.io/badge/3.-Analyze_Results-d946ef?style=for-the-badge)](#) ➔
[![Pivot IOCs](https://img.shields.io/badge/4.-Pivot_IOCs-ec4899?style=for-the-badge)](#)

</div>

<br/>

## ▌ Architecture & Features

- **Fully Client-Side:** No backend servers, no APIs, complete data privacy.
- **Multi-format Support:** Accepts `.EML`, `.MSG`, `.TXT`, and raw paste input.
- **Real-time Analytics:** Anonymous usage telemetry via Firebase (no PII collected).
- **Dark-aware UI:** Clean, professional interface optimized for long analyst shifts.

<br/>

## ▌ Technology Stack

<div align="center">
  <a href="https://skillicons.dev">
    <img src="https://skillicons.dev/icons?i=vue,ts,tailwind,vite,firebase,html,css" alt="Technology Stack" />
  </a>
</div>

<br/>

## ▌ Security & Privacy

We take data security seriously. MailScope is built on a **Strict Privacy Guarantee**:

1. **Local Execution:** Your emails never leave your browser. All parsing algorithms run directly on your machine.
2. **No Data Storage:** We do not log, store, or transmit your forensic files or investigation results.
3. **Open Source:** The entire codebase is public and fully auditable by the security community.

<br/>

## ▌ About The Creator

**Mahmoud-Na**  
*Cybersecurity Enthusiast | SOC Operations | Threat Detection*

[![GitHub](https://img.shields.io/badge/GitHub-mahmoudnazmy-181717?style=flat-square&logo=github)](https://github.com/mahmoudnazmy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Mahmoud_Na-0077b5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mahmoud-n/)

<br/>

---

<div align="center">
  <i>Built for analysts, by an analyst.</i> <br/>
  <b>© 2025 Mahmoud-Na. All rights reserved.</b>
</div>
