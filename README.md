# 🦉 OBalancer

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OWeb-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.1-cyan?style=flat-square"/>
</p>

> **OBalancer** — Load Balancing & Infrastructure Detector

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OBalancer is a web-infrastructure reconnaissance tool that detects load balancing, CDN, WAF and TLS characteristics of a target. It analyses multi-resolver DNS answers for round-robin and geographic balancing, inspects HTTP header/cookie/RTT variance for load balancers, and fingerprints 12+ CDN providers. TLS inspection and IP geolocation round out an infrastructure profile that can be exported for reporting.

---

## ✨ Features

- DNS load-balancing detection via multi-resolver A/AAAA analysis
- HTTP load-balancer detection from header, cookie, RTT and ETag variance
- CDN fingerprinting across 12+ providers
- WAF detection through probing and header heuristics
- TLS cipher suite, certificate and HSTS inspection
- IP geolocation and JSON/TXT export with a scorecard view

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OBalancer
./OBalancer --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
