## Overview
ENITF is a lightweight but extensible cybersecurity tool designed to map live network activity to system processes, enrich findings with threat intelligence, and flag suspicious behaviour for rapid triage.

This tool is built for:
- SOC Analysts (L1/L2)
- Incident Responders
- Red Team Operators
- Security Engineers
---

## Core Capabilities

- 🔍 Network Connection Discovery (Port-based or full scan)
- 🧠 Process Attribution (PID → Process → Executable Path)
- 🔐 File Hashing (SHA256)
- 🌐 Threat Intelligence Integration (VirusTotal)
- 🚨 Detection Engine (Anomaly-based flagging)
- 📊 HTML Reporting (Executive-ready output)

---

## Architecture
Port → Connection → PID → Process → File → Hash → Threat Intel → Detection → Report

---

## Installation

```bash
git clone https://github.com/yourusername/enitf.git
cd enitf
pip install -r requirements.txt
