# Moein Fatehi

**Application security and penetration testing lead · Burp Suite extension author · Smart contract security researcher**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-moeinfatehi-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moeinfatehi)
[![X](https://img.shields.io/badge/X-@MoeinFatehi-000000?style=flat&logo=x&logoColor=white)](https://x.com/MoeinFatehi)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-moeinfatehi-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/moeinfatehi)
[![Email](https://img.shields.io/badge/Email-moein.fatehi@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:moein.fatehi@gmail.com)

I'm a penetration tester and security team lead focused on web, API and mobile application security. I have led vulnerability assessment and penetration testing (VAPT) teams and worked on more than 1,000 enterprise penetration testing projects as a tester, project manager and team lead. I also build open-source Burp Suite extensions and vulnerable-by-design labs, so testers find real issues faster and learners can practise safely.

## Highlights

- **1,000+ enterprise penetration tests** across web applications, APIs, Android and iOS apps, desktop software, networks and infrastructure.
- **Two extensions in PortSwigger's BApp Store:** [Backup Finder](https://portswigger.net/bappstore/466bc6cbf5bb4449b56af7bd9c0000ea) and [CVSS Calculator](https://portswigger.net/bappstore/e2209cdad8474342a695b2e279c294f0).
- **560+ GitHub stars** on open-source security tools and **14,000+ Docker Hub pulls** of my training labs.
- **CTF champion** with multiple first-place finishes as part of the DCUA team.

## Burp Suite extensions

| Extension | What it does | Install |
|---|---|---|
| [Backup Finder](https://github.com/moeinfatehi/Backup-Finder) | Finds backup, old, temporary and unreferenced files that leak sensitive data, using payloads generated from the target's own structure (OWASP WSTG-CONF-04) | [BApp Store](https://portswigger.net/bappstore/466bc6cbf5bb4449b56af7bd9c0000ea) |
| [Admin Panel Finder](https://github.com/moeinfatehi/Admin-Panel_Finder) | Enumerates exposed admin panels and login pages with 1,000+ built-in payloads and technology-aware wordlists (OWASP WSTG-CONF-05) | [Release](https://github.com/moeinfatehi/Admin-Panel_Finder/releases) |
| [PassiveDigger](https://github.com/moeinfatehi/PassiveDigger) | Passively analyses proxied traffic for SQL errors, reflected parameters, LFI hints, serialized data, weak cookie flags and missing security headers | [Release](https://github.com/moeinfatehi/PassiveDigger/releases) |
| [CVSS Calculator](https://github.com/moeinfatehi/CVSS_Calculator) | Scores vulnerabilities with CVSS v2 and v3.1 offline, without leaving Burp Suite | [BApp Store](https://portswigger.net/bappstore/e2209cdad8474342a695b2e279c294f0) |

## Vulnerable-by-design labs

Self-contained Docker labs for practising common web vulnerabilities and filter bypasses.

| Lab | Vulnerability class | Image |
|---|---|---|
| [XSS challenges](https://github.com/moeinfatehi/xss_vulnerability_challenges) | Cross-site scripting and XSS filter bypasses | [Docker Hub](https://hub.docker.com/r/moeinfatehi/xss_vulnerability_challenges) |
| [File upload scenarios](https://github.com/moeinfatehi/file_upload_vulnerability_scenarios) | Unrestricted file upload and upload-filter bypasses leading to code execution | [Docker Hub](https://hub.docker.com/r/moeinfatehi/file_upload_vulnerabilities) |
| [LFI to RCE](https://github.com/moeinfatehi/lfi-to-rce-scenario) | Local file inclusion escalated to remote code execution | [Docker Hub](https://hub.docker.com/r/moeinfatehi/lfi-to-rce-scenario) |
| [RFI scenarios](https://github.com/moeinfatehi/rfi_vulnerability_scenarios) | Remote file inclusion, one new bypass technique per challenge | [Docker Hub](https://hub.docker.com/r/moeinfatehi/rfi_vulnerability_scenarios) |
| [CAPTCHA logic bypass](https://github.com/moeinfatehi/captcha_logical_bypass_scenarios) | Broken CAPTCHA logic that re-enables brute-force attacks | [Docker Hub](https://hub.docker.com/r/moeinfatehi/captcha_logical_bypass_scenarios) |
| [DVWA behind ModSecurity](https://github.com/moeinfatehi/dvwa-modsecurity-waf) | Attacking a web app protected by a ModSecurity WAF and tuning its rules | Docker Compose |

## Courses and research

- **[Linux for Cyber Security](https://github.com/moeinfatehi/LinuxForCyberSecurityCourse):** an open course with lectures, assignments and scripts, from Linux fundamentals to boot security, firewalls, SSH and hardening.
- **[Awesome Smart Contract Security](https://github.com/moeinfatehi/Awesome-Smart-Contract-Security):** a curated guide to Solidity vulnerabilities (SWC, OWASP), audit tools, papers and courses.
- **[Cosmos Chain Security](https://github.com/moeinfatehi/CosmosChainSecurity):** a security guide for Cosmos SDK chains covering IBC, validators and DEXs, with an Osmosis case study.

## Areas of expertise

Web application and API penetration testing · Mobile application security (Android, iOS) · OWASP WSTG and Top 10 · Burp Suite extension development in Java · Vulnerability scoring and management (CVSS) · Smart contract and blockchain security · Leading security testing teams

---

Found a bug in one of my tools or labs? Open an issue on its repository. For anything else, reach me on [LinkedIn](https://www.linkedin.com/in/moeinfatehi).
