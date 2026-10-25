# 🦉 OBruteSSH

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OAttack%20/%20Offensive-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1.0-cyan?style=flat-square"/>
</p>

> **OBruteSSH** — SSH Credential Audit Suite

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OBruteSSH is an SSH credential-audit suite for authorised security testing, offering wordlist brute force, single-credential tests, key-based authentication and credential stuffing. It adds adaptive threading, smart rate-limiting, CIDR/range expansion, banner fingerprinting and an SSH-alive pre-scan to work efficiently across many hosts. Successful sessions can run post-auth commands, and results export to CSV, JSON, TXT and HTML.

---

## ✨ Features

- Wordlist brute force, single-credential, key-based and credential-stuffing modes
- Adaptive threading with smart rate-limiting and transient-error retry
- CIDR / IP-range expansion with a thread-safe SSH-alive pre-scan cache
- SSH banner fingerprinting and duplicate-credential skipping
- Post-auth interactive command runner with a custom command editor
- Export to CSV, JSON, TXT and HTML with ETA and attempts/sec

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OBruteSSH
./OBruteSSH --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
