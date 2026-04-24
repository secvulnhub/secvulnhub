# SecVulnHub

Open-source security tooling built by practitioners. Every tool is real-world tested, clearly documented, and maintained by the community.

[![License: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE) [![Discord](https://img.shields.io/badge/discord-join-5865f2.svg)](https://discord.gg/SecVulnHub)

---

## What this is

SecVulnHub is a curated repository of offensive security tools built for people who use them in the field. The emphasis is on tools that solve real problems — not demo code or thin wrappers around existing utilities.

The **100-Day Gauntlet** (starting June 10, 2025) is a public commitment to ship one new tool every five days across five security domains.

---

## Tools

### Core

| Tool | Description | Status |
|------|-------------|--------|
| **SecV** | Compiled Go shell that loads security modules written in any language. The engine powering the arsenal. | Active |

### Recon & Intelligence

| Tool | Description | Status |
|------|-------------|--------|
| **Port Scanner Plus** | Advanced port enumeration with multi-engine scanning and service fingerprinting | Ready |
| **Subdomain Hunter** | Subdomain discovery and validation with multiple resolver strategies | Ready |
| **DNS Enum Suite** | DNS analysis with zone transfer detection and record enumeration | In Development |
| **OSINT Gatherer** | Automated OSINT collection across domains, people, and infrastructure | Ready |
| **Network Mapper** | Network topology discovery with host profiling and CVE correlation | In Development |

### Web Application Testing

| Tool | Description | Status |
|------|-------------|--------|
| **Web Fuzzer Pro** | Adaptive fuzzing with payload optimization and response analysis | Ready |
| **Config Auditor** | Configuration security analysis across web stacks and frameworks | Ready |
| **SSL/TLS Scanner** | Certificate and protocol testing — ciphers, chain validation, known weaknesses | Ready |
| **CMS Vuln Scanner** | Security testing for WordPress, Joomla, Drupal, and similar platforms | In Development |
| **API Security Tester** | REST and GraphQL validation — auth bypass, injection, rate limit testing | Planned |

### Exploitation Utilities

| Tool | Description | Status |
|------|-------------|--------|
| **XSS Payload Gen** | Context-aware XSS payload generation for modern CSP and WAF bypass | Ready |
| **SQL Injection Tester** | Injection testing with blind, error-based, time-based, and OOB techniques | Ready |
| **CSRF Token Analyzer** | CSRF analysis and token entropy validation | In Development |
| **Payload Generators** | Payload creation for multiple attack vectors with full encoding support | Ready |
| **Reverse Shell Kit** | Multi-platform reverse connection utilities with obfuscation options | Ready |
| **PrivEsc Checker** | Privilege escalation enumeration for Linux and Windows systems | In Development |

### Mobile Security

| Tool | Description | Status |
|------|-------------|--------|
| **APK Analyzer** | Android app testing — manifest, permissions, CVE cross-referencing, secret scanning | Planned |
| **iOS Security Tester** | iOS app vulnerability assessment via libimobiledevice | Planned |

### Forensics & Analysis

| Tool | Description | Status |
|------|-------------|--------|
| **Log Analyzer** | Log parsing with anomaly detection, pattern correlation, and timeline reconstruction | In Development |
| **Traffic Analyzer** | Deep packet inspection and protocol analysis for network forensics | In Development |

### Automation & Utilities

| Tool | Description | Status |
|------|-------------|--------|
| **Report Generator** | Automated security assessment report generation with customizable templates | Ready |
| **Hash Cracker** | Multi-algorithm hash cracking with wordlist and rule-based attack modes | Ready |
| **Encoding Decoder** | Universal encoding/decoding — Base64, URL, hex, HTML, Unicode, and more | Ready |

---

## Roadmap

The gauntlet runs June 10 – September 18, 2025. One tool ships every five days.

| Phase | Days | Focus |
|-------|------|-------|
| 1 | 1–20 | Recon & intelligence gathering |
| 2 | 21–40 | Vulnerability detection and assessment |
| 3 | 41–60 | Exploitation frameworks and utilities |
| 4 | 61–80 | Automation and workflow integration |
| 5 | 81–100 | Forensics and incident response |

---

## Contributing

We accept contributions that meet these criteria:

- Solves a real security challenge not already covered by an existing tool
- Deployable in under five minutes following the documentation
- Passes a security review and includes tests
- Adds unique value — no duplication of existing tools

**Process:** Fork → Develop → Document → Test → Pull Request → Review → Merge

See [`CONTRIBUTING.md`](CONTRIBUTING.md) for directory structure requirements, the `install.sh` / `test.sh` conventions, and the full review checklist.

### Contributor recognition

| Tier | Threshold |
|------|-----------|
| Legendary | 10+ tools |
| Elite | 5–9 tools |
| Veteran | 2–4 tools |
| Contributor | 1 tool |

---

## Legal

All tools are for **authorized security testing only.**

You are responsible for ensuring you have explicit permission before running any tool against a target system. Unauthorized use is illegal in most jurisdictions. Responsible disclosure: follow the affected vendor's disclosure policy.

---

## Community

- **Discord** — [discord.gg/SecVulnHub](https://discord.gg/SecVulnHub) — contributor coordination, questions, announcements
- **Issues** — bug reports and feature requests
- **Discussions** — proposals and ideas
- **Security reports** — `security@secvulnhub.local`

---

MIT License. See [`LICENSE`](LICENSE).
