<div align="center">

# 🦉 OBalancer

**Load Balancing Detector**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

*Part of the [OwlSec](https://owlsec.org) Toolkit*
```
██████╗ ██████╗  █████╗ ██╗      █████╗ ███╗   ██╗ ██████╗███████╗██████╗
██╔═══██╗██╔══██╗██╔══██╗██║     ██╔══██╗████╗  ██║██╔════╝██╔════╝██╔══██╗
██║   ██║██████╔╝███████║██║     ███████║██╔██╗ ██║██║     █████╗  ██████╔╝
██║   ██║██╔══██╗██╔══██║██║     ██╔══██║██║╚██╗██║██║     ██╔══╝  ██╔══██╗
╚██████╔╝██████╔╝██║  ██║███████╗██║  ██║██║ ╚████║╚██████╗███████╗██║  ██║
 ╚═════╝ ╚═════╝ ╚═╝  ╚═╝╚══════╝╚═╝  ╚═╝╚═╝  ╚═══╝ ╚═════╝╚══════╝╚═╝  ╚═╝
                  DNS + HTTP + CDN + WAF Detection
```

</div>

---

## 📌 Overview

**OBalancer** is a load balancing detection tool that identifies and fingerprints infrastructure layers in front of a target — including DNS-based load balancers, HTTP load balancers, CDN providers, and Web Application Firewalls (WAF).

---

## 🖥️ Module Reference

### 🔍 Detection

| Option | Module | Description |
|--------|--------|-------------|
| `[1]` | Full Scan | Run all detection modules: DNS + HTTP + CDN + WAF |
| `[2]` | DNS LB | Detect DNS-based load balancing |
| `[3]` | HTTP LB | Detect HTTP load balancing via header analysis |
| `[4]` | CDN Detect | Fingerprint CDN provider (Cloudflare, Akamai, Fastly, etc.) |
| `[5]` | WAF Detect | Probe and identify Web Application Firewall presence |

### 📊 Results

| Option | Description |
|--------|-------------|
| `[6]` | View Results — Display last scan summary |
| `[7]` | Export JSON — Save results to a JSON file |

---

## 🎯 Use Cases

- Map target infrastructure during recon phase
- Identify CDN providers and WAF solutions
- Detect DNS round-robin or geo-based load balancing
- Understand HTTP routing behavior across multiple backends

---

## ⚙️ Requirements

- Linux (any distro)
- The tool is pre-built — no Python installation needed

---

## ⚠️ Legal Disclaimer

> **THIS TOOL IS FOR EDUCATIONAL AND AUTHORIZED AUDIT PURPOSES ONLY.**  
> Unauthorized scanning of systems is illegal and unethical.  
> The developer is not responsible for any misuse.

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

> 🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
