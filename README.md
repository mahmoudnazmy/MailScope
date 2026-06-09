<div align="center">

<br/>

```
 ███╗   ███╗ █████╗ ██╗██╗      ███████╗ ██████╗ ██████╗ ██████╗ ███████╗
 ████╗ ████║██╔══██╗██║██║      ██╔════╝██╔════╝██╔═══██╗██╔══██╗██╔════╝
 ██╔████╔██║███████║██║██║      ███████╗██║     ██║   ██║██████╔╝█████╗  
 ██║╚██╔╝██║██╔══██║██║██║      ╚════██║██║     ██║   ██║██╔═══╝ ██╔══╝  
 ██║ ╚═╝ ██║██║  ██║██║███████╗ ███████║╚██████╗╚██████╔╝██║     ███████╗
 ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝╚══════╝ ╚══════╝ ╚═════╝ ╚═════╝ ╚═╝     ╚══════╝
```

**Professional Email Investigation & Forensics Platform**

<br/>

[![Live Demo](https://img.shields.io/badge/Live_Demo-Visit_Platform-6366f1?style=for-the-badge&logo=github)](https://mahmoudnazmy.github.io/MailScope/)
[![Vue 3](https://img.shields.io/badge/Vue-3.x-42b883?style=for-the-badge&logo=vue.js&logoColor=white)](https://vuejs.org)
[![TypeScript](https://img.shields.io/badge/TypeScript-5.x-3178c6?style=for-the-badge&logo=typescript&logoColor=white)](https://www.typescriptlang.org)
[![License](https://img.shields.io/badge/License-MIT-0ea5e9?style=for-the-badge)](LICENSE)

<br/>

---

</div>

<br/>

## Overview

**MailScope** is a client-side, open-source email investigation platform designed to assist Security Operations Center (SOC) analysts, Digital Forensics and Incident Response (DFIR) practitioners, and cybersecurity researchers in conducting deep, structured email investigations — directly in the browser, without any backend or data transmission.

Built with precision for modern threat landscapes, MailScope provides granular visibility into the technical anatomy of email messages, enabling analysts to rapidly identify phishing campaigns, Business Email Compromise (BEC), spoofing attacks, and malicious payloads.

<br/>

---

## Core Modules

<br/>

### `[01]` Header Analysis
> Deep-dive into raw internet message headers with full forensic reconstruction.

- Parses and visualizes the complete **SMTP relay chain** with hop-by-hop timing analysis
- Validates **SPF**, **DKIM**, **DMARC**, and **ARC** authentication records cryptographically
- Detects **header spoofing**, mismatched sender paths, and forged `Reply-To` fields
- Supports `.EML` file upload and raw header paste input
- Extracts and pivots on **Indicators of Compromise (IOCs)** including IPs, domains, hashes, and URLs

<br/>

### `[02]` Body Analysis
> Forensic inspection of email body content for malicious intent signals.

- Scans for **malicious URLs** with redirect chain tracking and punycode detection
- Identifies **brand impersonation** patterns targeting major financial and tech organizations
- Deobfuscates and decodes **HTML payload obfuscation** techniques (Base64, hex encoding, CSS tricks)
- Detects **social engineering** language patterns and psychological manipulation tactics
- Flags suspicious attachment MIME types and embedded exploit indicators

<br/>

### `[03]` Full Email Investigation
> Unified correlated analysis combining header and body forensics in a single report.

- Processes complete `.EML` / `.MSG` files with full MIME tree reconstruction
- Delivers a consolidated, **high-fidelity investigation report** with unified threat scoring
- Correlates header authentication, routing anomalies, and body-level threat signals
- Produces a severity-graded findings summary (Critical → Low) with actionable context

<br/>

---

## How to Use

> **MailScope runs entirely in your browser. No account required. No data leaves your device.**

**Step 1** — Navigate to the module that matches your investigation scope:
- `Header Analysis` for raw header / `.EML` files with routing & auth focus
- `Body Analysis` for email body content, HTML source, or plain text payloads
- `Full Email` for complete `.EML` / `.MSG` files requiring end-to-end investigation

**Step 2** — Upload a file or paste raw content directly into the input area.

**Step 3** — Review the structured findings report. Each finding includes:
- Severity classification (Critical / High / Medium / Low)
- Technical context and explanation
- Recommended analyst actions

**Step 4** — Use the IOC extraction panel to pivot indicators to external threat intelligence platforms (VirusTotal, Shodan, AbuseIPDB, and more).

<br/>

---

## Platform Features

| Feature | Description |
|---|---|
| **Zero Backend** | Fully client-side — no servers, no data collection |
| **Real-time Analytics** | Live usage telemetry via Firebase Firestore |
| **Multi-format Support** | Accepts `.EML`, `.MSG`, `.TXT`, and raw paste input |
| **IOC Extraction** | Automated extraction of IPs, URLs, domains, email addresses, and file hashes |
| **Threat Scoring** | Deterministic severity scoring across all finding categories |
| **MIME Tree Viewer** | Full MIME structure visualization for multipart messages |
| **Dark-aware UI** | Clean, professional interface optimized for analyst workflows |
| **Open Source** | Fully auditable codebase — no hidden logic |

<br/>

---

## Technology Stack

| Layer | Technology |
|---|---|
| UI Framework | Vue.js 3 (Composition API) |
| Language | TypeScript 5 |
| Styling | Tailwind CSS |
| Build Tool | Vite 8 |
| State Management | Pinia |
| Cloud Telemetry | Firebase Firestore |
| Data Visualization | Chart.js / vue-chartjs |
| Icons | Lucide Icons |

<br/>

---

## Security & Privacy

MailScope is designed with analyst privacy as a core principle:

- **No email content is transmitted** — all parsing and analysis is performed locally in the browser
- **Firebase** is used exclusively for **anonymous aggregate usage counters** (total visits, analysis counts) — no email data, IP addresses, or user identifiers are stored
- The codebase is fully open source and auditable

<br/>

---

## About The Creator

**Mahmoud-Na** — Cybersecurity Enthusiast with a focus on Security Operations (SOC), Threat Detection, Email Security, Threat Hunting, and Digital Forensics.

MailScope was built as a practical, production-quality tool to improve email investigation workflows and provide accessible, professional-grade tooling for the cybersecurity community.

[![GitHub](https://img.shields.io/badge/GitHub-mahmoudnazmy-181717?style=flat-square&logo=github)](https://github.com/mahmoudnazmy)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-mahmoud--n-0077b5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/mahmoud-n/)

<br/>

---

## License

```
MIT License

Copyright (c) 2025 Mahmoud-Na

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
```

<br/>

---

<div align="center">

**MailScope** · Built for analysts, by an analyst.

*© 2025 Mahmoud-Na. All rights reserved.*

</div>
