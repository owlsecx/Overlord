# 🦉 Overlord

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **Overlord** — Authorized SMB enumeration with MITRE ATT&CK risk scoring (null-session audit, lab defaults)

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview


Overlord is a command-and-control orchestration framework for authorized red-team operations that coordinates tasking and results across simulated agents. It manages listeners, queues operator commands and aggregates responses in a single console. It is intended strictly for authorized adversary-simulation on systems you own or are permitted to test.

---

## ✨ Features


- Orchestration of operator tasking across managed agents/listeners
- Command queueing and result aggregation in one console
- Listener/session management for simulated engagements
- Structured logging of operations for after-action review
- Configurable, authorization-gated operation workflow
- Offline --self-test for safe verification

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage


```bash
./Overlord
./Overlord --self-test
./Overlord --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
