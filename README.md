<div align="center">

<h1>🛡️ Cybersecurity Internship Portfolio</h1>

<p>
  <img src="https://img.shields.io/badge/Status-Completed%20Dec%202025-22c55e?style=for-the-badge" alt="Status"/>
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-0ea5e9?style=for-the-badge" alt="License"/></a>
  <img src="https://img.shields.io/badge/Python-3.8%2B-3776AB?logo=python&logoColor=white&style=for-the-badge" alt="Python"/>
  <img src="https://img.shields.io/badge/Platform-Windows%20%7C%20Linux%20%7C%20macOS-8b5cf6?style=for-the-badge" alt="Platform"/>
  <img src="https://img.shields.io/badge/Tools-Flask%20%7C%20Scapy%20%7C%20Snort-f97316?style=for-the-badge" alt="Tools"/>
</p>

<p>A curated set of network security projects completed as part of the CodeAlpha Cybersecurity Internship. This portfolio showcases hands‑on work in packet capture, real‑time dashboards, rule‑based intrusion detection, secure coding review, and security awareness.</p>

<p>
  <a href="#tasks-overview">Tasks</a> •
  <a href="#quick-start">Quick Start</a> •
  <a href="#repository-structure">Structure</a> •
  <a href="#disclaimer">Disclaimer</a>
</p>

</div>

---

## ✨ Highlights
- Modern, neon‑styled Network Sniffer dashboard with live charts and secure auth
- Python/Scapy NIDS with rule matching, JSON logging, and visualization
- Practical phishing awareness content and secure coding review deliverables
- Clean structure, clear docs, and copy‑pasteable commands for Windows

---

## Tasks Overview

### Task 1 — Network Sniffer (Flask + Scapy)
A real‑time packet sniffer with a polished cyberpunk UI and export tools.
- Features: live capture, filtering, search/sort, protocol/category stats, PCAP/CSV export, session login
- Quick path: see [Task 1/Network Sniffer](Task%201/Network%20Sniffer)
- App entry: [Task 1/Network Sniffer/app.py](Task%201/Network%20Sniffer/app.py)

### Task 2 — Phishing Awareness Training
Educational deliverables focused on phishing and social engineering.
- Deliverables: [Task 2/Presentation - Phishing Awareness.pdf](Task%202/Presentation%20-%20Phishing%20Awareness.pdf), [Task 2/Presentation - Phishing Awareness.pptx](Task%202/Presentation%20-%20Phishing%20Awareness.pptx)

### Task 3 — Secure Coding Review
Security audit and recommendations for safer software development.
- Deliverable: [Task 3/Documentation - Secure Coding Review.pdf](Task%203/Documentation%20-%20Secure%20Coding%20Review.pdf)

### Task 4 — Network Intrusion Detection System (NIDS)
Custom Python NIDS plus Snort configs and visualization.
- Quick path: [Task 4/Network Intrusion Detection System](Task%204/Network%20Intrusion%20Detection%20System)
- Python NIDS: [python_nids/nids.py](Task%204/Network%20Intrusion%20Detection%20System/python_nids/nids.py)
- Viz tool: [visualization/dashboard.py](Task%204/Network%20Intrusion%20Detection%20System/visualization/dashboard.py)

---

## Quick Start

### Windows — Task 1: Network Sniffer
Requires Administrator privileges for packet sniffing.

```powershell
# From repo root
cd "Task 1/Network Sniffer"

python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

# Run (as Administrator)
python app.py
# Then open http://localhost:5000 (default login: admin / admin123)
```

### Windows — Task 4: Python NIDS + Visualization
```powershell
# From repo root
cd "Task 4/Network Intrusion Detection System/python_nids"

python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt

# Run NIDS (as Administrator)
python nids.py

# When finished, visualize alerts
cd ..\visualization
python dashboard.py
```

---

## Requirements
- Python 3.8+
- Windows/macOS/Linux (Admin/Root required for sniffing)
- Per‑task Python dependencies listed in each `requirements.txt`

---

## Repository Structure

```
Task 1/
  Network Sniffer/
    app.py, templates/, static/, requirements.txt, README.md
Task 2/
  Presentation - Phishing Awareness.(pdf|pptx)
Task 3/
  Documentation - Secure Coding Review.pdf
Task 4/
  Network Intrusion Detection System/
    python_nids/ (nids.py, requirements.txt, logs/)
    snort_config/ (snort.conf, local.rules)
    visualization/ (dashboard.py)
Tasks/
  Cyber Security Tasks & Instructions — CodeAlpha.pdf
LICENSE
```

---

## Disclaimer
This repository contains work completed for the CodeAlpha Cybersecurity Internship and is provided strictly for educational and demonstration purposes. Use packet capture, intrusion detection, and any security tooling only on systems and networks you own or have explicit, written permission to test. Ensure compliance with local laws, organizational policies, and internship guidelines at all times. The author assumes no responsibility for misuse.

---

## Author & License
- Author: Mandar Kajbaje
- License: MIT — see [LICENSE](LICENSE)
