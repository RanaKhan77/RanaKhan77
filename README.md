<div align="center">

<img src="assets/header.svg" width="100%" alt="Rana Khan — security researcher and bug bounty hunter from Bangladesh, founder of 2mny.com — animated radar scanner banner" />

# 👋 Rana Khan

### 🛡️ Security Researcher · Bug Bounty Hunter · Founder of [2mny.com](https://2mny.com)

**I find weaknesses before attackers do.** I'm a security researcher from **Bangladesh 🇧🇩** hunting
web vulnerabilities — and building the tools that make hunting repeatable: the **317-module bug bounty
platform & commercial scanner** at [2mny.com](https://2mny.com), open-source scanners, and OSINT that
shows what attackers already know. Everything I build is defensive: detect it, prove it, fix it first.

[![Website](https://img.shields.io/badge/🌐_2MNY_Security-2mny.com-00C853?style=for-the-badge)](https://2mny.com)
[![Free Scan](https://img.shields.io/badge/⚡_Free_Scan-Protect_Your_Site-FF5722?style=for-the-badge)](https://2mny.com/free-security-scan)
[![Blog](https://img.shields.io/badge/📖_Security_Blog-Guides_&_Research-2196F3?style=for-the-badge)](https://2mny.com/blog)
[![GitHub](https://img.shields.io/badge/⭐_Star_My_Work-RanaKhan77-181717?style=for-the-badge)](https://github.com/RanaKhan77?tab=repositories)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-ranakhan-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/ranakhan/)

</div>

---

## 🔭 What I Do

<div align="center">

| | Focus | In practice |
|:---:|:---|:---|
| 🎯 | **Web Vulnerability Scanning** | XSS · SQLi · SSRF · SSTI · command injection · subdomain takeover · OWASP Top 10 — CVSS-scored, evidence-backed |
| ⚡ | **Bug Bounty Automation** | Recon pipelines & deterministic engines that compress triage from days to minutes |
| 🕵️ | **OSINT & Exposure Intel** | Breach collections, stealer logs, username grids — know exactly what's already exposed |

</div>

---

## 🛡️ What I've Built

Everything below is protection tooling — it finds weaknesses **before attackers do**, so website
owners can fix them first. Detection, evidence, and a clear fix plan. Nothing I build is for
attacking anyone.

### 🚀 [Website Vulnerability Scanner — Community Edition](https://github.com/RanaKhan77/Website-Vulnerability-Scanner)
**The only web scanner that shows you what it did NOT check — fully-deterministic, self-hostable protection.**

| | |
|---|---|
| 🧩 **218 scanner modules** | Finds XSS · SQLi · SSRF · SSTI · command injection · subdomain takeover · OWASP Top 10 risks |
| 🤖 **AI-stack safety** | MCP server auditing · LLM Top-10 exposure · agent panels · leaked AI keys |
| 📄 **Evidence-backed reports** | CVSS-scored findings, HTML/PDF, technical + customer variants |
| 🏠 **100% self-hosted** | One Docker command — no API keys, no token billing, no vendor lock |
| ⚔️ **Battle-tested** | False-positive guards, soft-404 baselining, WAF detection, ownership gating |
| ⚖️ **Truly open** | Apache-2.0 core, MIT tools only — free forever |

```bash
git clone https://github.com/RanaKhan77/website-vulnerability-scanner.git   # your own 218-module protection lab
```

### 🕵️ [Exposure-Check-OSINT](https://github.com/RanaKhan77/Exposure-Check-OSINT)
**Self-hosted personal exposure checker — is your email, username, phone or password leaked?**

| | |
|---|---|
| 🔎 **25 keyless sources** | Breach collections · infostealer logs · COMB 11B+ credentials · HIBP k-anonymity · 200-platform username grid |
| 🔑 **Zero API keys** | No accounts, no rate-limit roulette, no telemetry — one Docker command and it runs |
| 🧠 **Zero AI, on purpose** | Deterministic three-state verdicts: exposed / clear / unavailable — a dead source never fakes a pass |
| 🔐 **Privacy by design** | Salted hashes + masked identifiers only; password checks match in your browser (k-anonymity) |
| 📄 **Evidence reports** | Printable per-source report with honest 0–100 exposure score — [live landing page →](https://ranakhan77.github.io/Exposure-Check-OSINT/) |
| 📤 **Data out (v1.1)** | JSON + CSV export for every check · confidence-tiered username hits (confirmed vs probable) |
| 🩺 **ec:doctor (v1.1)** | One-command install self-test: 25-source reachability, storage, database, migrations — seconds, zero network cost |

```bash
git clone https://github.com/RanaKhan77/Exposure-Check-OSINT.git   # know what attackers already know
```

### ☁️ [Awesome Cyber Security Heaven](https://github.com/RanaKhan77/awesome-cyber-security-heaven)
**A hand-curated, license-verified map of 1435 free cybersecurity protection tools — built for discovery.**

| | |
|---|---|
| 🏰 **14 themed realms** | Pentest arsenal · hardening · threat intel · OSINT · DFIR · DevSecOps · AI security |
| 🔬 **License-verified** | Every flagship entry checked via GitHub API — copyleft/freemium tagged inline |
| 🆓 **100% free** | No paywalls, no AI-gated entries, no sponsored placements |
| 🔄 **Quarterly re-verification** | Dead links swept, activity re-checked, standards enforced |

⭐ *If you defend systems for a living — or you're learning to — this is the shortcut list.* — [browse the realms →](https://github.com/RanaKhan77/awesome-cyber-security-heaven)

### ⚡ [2MNY Security Scan](https://github.com/marketplace/actions/2mny-security-scan) — GitHub Action
**Free CI security checks on every push — one line in your workflow.**

| | |
|---|---|
| 🔍 **What it checks** | TLS/SSL health · security headers (HSTS/CSP) · cookie flags |
| 📄 **What you get** | A full evidence-backed report from 2mny.com, right in your Actions log |
| 🆓 **Cost** | Free — public repos, no API keys, no setup beyond one line |

```yaml
- uses: RanaKhan77/2mny-security-scan@v1
  with:
    target: https://example.com
```

### 🌐 [2MNY Security](https://2mny.com) — the managed protection platform
<a href="https://2mny.com"><img src="assets/2mny-globe-banner.jpg" width="820" alt="2MNY Security — bug bounty platform and free website security scanning · 2mny.com" /></a>

The full **317-module engine** with continuous attack monitoring, attack-surface diffing and
redacted customer reporting — plus a bug bounty platform — protecting teams that want the coverage
without hosting it themselves. Run the free instant check at [**2mny.com**](https://2mny.com) — no signup needed.

### 🇧🇩 [Awesome Bangladesh](https://github.com/RanaKhan77/Awesome-Bangladesh)
**The curated map of Bangladesh's open source, open data and free APIs — community-built.**

| | |
|---|---|
| 📚 **What it is** | 380+ verified entries across 14 sections — datasets, Bangla NLP, fintech SDKs, civic tech, crisis-response and everyday apps |
| ✅ **Evidence-first curation** | Every entry live-verified with licence + Bangladesh-connection evidence; no star counts, no fluff |
| 📖 **Deep-dive guides** | 14 section handbooks with editor's picks, plus a [showcase site](https://ranakhan77.github.io/Awesome-Bangladesh/) |
| 🤝 **Community-built** | Open contributions with a firm verification process — suggest, verify, correct |

⭐ *The national directory for Bangladeshi developers — built to connect the whole ecosystem.* — [explore the list →](https://github.com/RanaKhan77/Awesome-Bangladesh)

---

## 🧰 Protection Focus

```text
🛡️ Web App Protection    Finds XSS · SQLi · SSRF · IDOR · auth flaws · race conditions — first
🔭 Attack-Surface Guard  Subdomain takeover · cert mining · exposed JS secrets · recon exposure
🤖 AI Stack Safety       MCP servers · LLM gateways · agent endpoints · vector DB exposure
🏗 CMS & Frameworks      WordPress · Laravel · Django · Rails · Joomla · Magento
🔗 Supply Chain Safety   OSV matching · outdated components · dependency risk
📡 Threat Monitoring     Infostealer leaks · defacement watch · ransomware tracking
🕵️ Personal Exposure     Email/username/phone/password/IP leak checks · breach & stealer-log intel
```

&nbsp;

<details open>
<summary><b>💻 Stack</b></summary>
&nbsp;

![PHP](https://img.shields.io/badge/PHP-8.4-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-12-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.13-3776AB?style=flat-square&logo=python&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![nuclei](https://img.shields.io/badge/nuclei-00C853?style=flat-square)
![nmap](https://img.shields.io/badge/nmap-00557F?style=flat-square)
![nikto](https://img.shields.io/badge/nikto-009688?style=flat-square)

</details>

---

## 📊 The Work, By Numbers

<div align="center">

![Protection Modules Built](https://img.shields.io/badge/Protection_Modules_Built-317-00C853?style=for-the-badge)
![Open-Source Modules](https://img.shields.io/badge/Open--Source_Modules-218-2196F3?style=for-the-badge)
![Tools_Curated](https://img.shields.io/badge/Tools_Curated-1435-FF6F00?style=for-the-badge)
![Free Forever](https://img.shields.io/badge/Free_Tier-Always_Available-00C853?style=for-the-badge)

<img height="170" src="assets/top-langs.svg" alt="Rana Khan — most used languages: PHP, Laravel, Python, Docker" />

</div>

---

## 🧭 Principles

> **Deterministic beats probabilistic in security.** Same target → same findings, every run.
> Evidence a CISO can defend in court — not "the model said so."

- 🛡️ **Protection first** — every scanner, every list, every guide exists to keep people safe from attackers
- 🔓 Open source where it matters, honest telemetry over fake DRM
- 🎯 Ownership-gated intrusive testing — authorize properly, test responsibly
- 🇧🇩 Building from Bangladesh for the world — and giving back along the way
- 🔁 Ship daily, verify everything, measure what actually protects people

---

<div align="center">

## 📡 Now

🔨 **Shipping** the next [Community Edition](https://github.com/RanaKhan77/Website-Vulnerability-Scanner) batch — 218 modules and climbing <br>
🛰️ **Growing [2mny.com](https://2mny.com)** — the 317-module bug bounty platform & commercial scanner <br>
📚 **Curating** [awesome-cyber-security-heaven](https://github.com/RanaKhan77/awesome-cyber-security-heaven) (1435 tools) & [Awesome-Bangladesh](https://github.com/RanaKhan77/Awesome-Bangladesh) <br>
💬 Questions or ideas? → [Community Discussions](https://github.com/RanaKhan77/Website-Vulnerability-Scanner/discussions)

### 🤝 Let's Connect

[![Email](https://img.shields.io/badge/📧_Email-2MNY_Security-D14836?style=for-the-badge)](https://2mny.com/contact)
[![LinkedIn](https://img.shields.io/badge/💼_LinkedIn-ranakhan-0A66C2?style=for-the-badge)](https://www.linkedin.com/in/ranakhan/)
[![Report a Vuln](https://img.shields.io/badge/🐞_Report_a_Vulnerability-Responsible_Disclosure-8B0000?style=for-the-badge)](https://2mny.com/.well-known/security.txt)
[![Community License](https://img.shields.io/badge/🔑_Free_License-Key_Instantly-00C853?style=for-the-badge)](https://2mny.com/community-license)

&nbsp;

**⭐ If my tools helped protect your site — a star keeps the mission moving. ⭐**

<img src="assets/footer.svg" width="100%" alt="Thanks for visiting — let's build a safer web · Rana Khan · 2mny.com · LinkedIn /in/ranakhan" />

<sub>Built with stubborn engineering discipline · 🇧🇩 Bangladesh → 🌍 A safer web for everyone</sub>

</div>
