<div align="center">

<img src="assets/profile-banner.jpg" width="100%" alt="Rana Khan — Cybersecurity Protector · Founder of 2MNY Security" />

# 👋 Rana Khan

### 🛡️ Cybersecurity Protector · Security Researcher · Founder of [2MNY Security](https://2mny.com)

**I build cybersecurity protection tools that run on *your* own hardware** — deterministic engines,
evidence-backed findings, CVSS-scored reports, zero AI lock-in, zero token billing.

🌍 *My mission: help keep the cyber world safe from attackers. Every tool I build exists to protect
people, teams and communities — and I'm proud to contribute to a safer digital Bangladesh and a
safer internet for everyone.*

&nbsp;

[![Website](https://img.shields.io/badge/🌐_2MNY_Security-2mny.com-00C853?style=for-the-badge)](https://2mny.com)
[![Free Scan](https://img.shields.io/badge/⚡_Free_Scan-Protect_Your_Site-FF5722?style=for-the-badge)](https://2mny.com/free-security-scan)
[![Blog](https://img.shields.io/badge/📖_Security_Blog-Guides_&_Research-2196F3?style=for-the-badge)](https://2mny.com/blog)
[![GitHub](https://img.shields.io/badge/⭐_Star_My_Work-RanaKhan77-181717?style=for-the-badge)](https://github.com/RanaKhan77?tab=repositories)

&nbsp;

</div>

---

## 🎯 What I Protect

Building protection tools that find weaknesses **before attackers do** — so website owners can fix
them first. Everything is defensive: detection, evidence, and a clear fix plan. Nothing I build is
for attacking anyone.

### 🚀 [Website Vulnerability Scanner — Community Edition](https://github.com/RanaKhan77/Website-Vulnerability-Scanner)
**The largest fully-deterministic, self-hostable website protection suite ever open-sourced.**

| | |
|---|---|
| 🧩 **200 scanner modules** | Finds XSS · SQLi · SSRF · SSTI · command injection · subdomain takeover · OWASP Top 10 risks |
| 🤖 **AI-stack safety** | MCP server auditing · LLM Top-10 exposure · agent panels · leaked AI keys |
| 📄 **Evidence-backed reports** | CVSS-scored findings, HTML/PDF, technical + customer variants |
| 🏠 **100% self-hosted** | One Docker command — no API keys, no token billing, no vendor lock |
| ⚔️ **Battle-tested** | False-positive guards, soft-404 baselining, WAF detection, ownership gating |

```bash
git clone https://github.com/RanaKhan77/website-vulnerability-scanner.git   # your own 200-module protection lab
```

### 🕵️ [Exposure-Check-OSINT](https://github.com/RanaKhan77/Exposure-Check-OSINT)
**Self-hosted personal exposure checker — is your email, username, phone or password leaked?**

| | |
|---|---|
| 🔎 **18 keyless sources** | Breach collections · infostealer logs · COMB 11B+ credentials · HIBP k-anonymity · 150-platform username grid |
| 🔑 **Zero API keys** | No accounts, no rate-limit roulette, no telemetry — one Docker command and it runs |
| 🧠 **Zero AI, on purpose** | Deterministic three-state verdicts: exposed / clear / unavailable — a dead source never fakes a pass |
| 🔐 **Privacy by design** | Salted hashes + masked identifiers only; password checks match in your browser (k-anonymity) |
| 📄 **Evidence reports** | Printable per-source report with honest 0–100 exposure score — [live landing page →](https://ranakhan77.github.io/Exposure-Check-OSINT/) |
| 📤 **Data out (v1.1)** | JSON + CSV export for every check · confidence-tiered username hits (confirmed vs probable) |
| 🩺 **ec:doctor (v1.1)** | One-command install self-test: 18-source reachability, storage, database, migrations — seconds, zero network cost |

```bash
git clone https://github.com/RanaKhan77/Exposure-Check-OSINT.git   # know what attackers already know
```

### ☁️ [Awesome Cyber Security Heaven](https://github.com/RanaKhan77/awesome-cyber-security-heaven)
**A hand-curated, license-verified map of almost 500 free cybersecurity protection tools — built for discovery.**

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
<a href="https://2mny.com"><img src="assets/2mny-globe-banner.jpg" width="820" alt="2MNY Security — free website security scanning platform · 2mny.com" /></a>

The full **287-module engine** with continuous attack monitoring, attack-surface diffing and
redacted customer reporting — protecting teams that want the coverage without hosting it themselves.
Run the free instant check at **[2mny.com](https://2mny.com)** — no signup needed.

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

![Protection Modules Built](https://img.shields.io/badge/Protection_Modules_Built-287-00C853?style=for-the-badge)
![Open-Source Modules](https://img.shields.io/badge/Open--Source_Modules-200-2196F3?style=for-the-badge)
![Tools_Curated](https://img.shields.io/badge/Tools_Curated-Almost_500-FF6F00?style=for-the-badge)
![Free Forever](https://img.shields.io/badge/Free_Tier-Always_Available-00C853?style=for-the-badge)

<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RanaKhan77&layout=compact&hide_border=true&theme=chartreuse-dark&langs_count=8" alt="Top languages" />

</div>

---

## 🛡️ Principles

> **Deterministic beats probabilistic in security.** Same target → same findings, every run.
> Evidence a CISO can defend in court — not "the model said so."

- 🛡️ **Protection first** — every scanner, every list, every guide exists to keep people safe from attackers
- 🔓 Open source where it matters, honest telemetry over fake DRM
- 🎯 Ownership-gated intrusive testing — authorize properly, test responsibly
- 🇧🇩 Building from Bangladesh for the world — and giving back along the way
- 🔁 Ship daily, verify everything, measure what actually protects people

---

<div align="center">

### 🤝 Let's Connect

[![Email](https://img.shields.io/badge/📧_Email-2MNY_Security-D14836?style=for-the-badge)](https://2mny.com/contact)
[![Report a Vuln](https://img.shields.io/badge/🐞_Report_a_Vulnerability-Responsible_Disclosure-8B0000?style=for-the-badge)](https://2mny.com/contact)
[![Community License](https://img.shields.io/badge/🔑_Free_License-Key_Instantly-00C853?style=for-the-badge)](https://2mny.com/community-license)

&nbsp;

**⭐ If my tools helped protect your site — star the repo, it keeps the mission funded. ⭐**

<sub>Built with stubborn engineering discipline · 🇧🇩 Bangladesh → 🌍 A safer web for everyone</sub>

</div>
