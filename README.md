# Moein Fatehi

**Founder and Managing Director of [HafezSecure](https://hafezsecure.ir/en) · Application security and penetration testing · Burp Suite extension author**

[![HafezSecure](https://img.shields.io/badge/HafezSecure-hafezsecure.ir-6C1C4F?style=flat)](https://hafezsecure.ir/en)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-moeinfatehi-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/moeinfatehi)
[![X](https://img.shields.io/badge/X-@MoeinFatehi-000000?style=flat&logo=x&logoColor=white)](https://x.com/MoeinFatehi)
[![Docker Hub](https://img.shields.io/badge/Docker_Hub-moeinfatehi-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/u/moeinfatehi)
[![Email](https://img.shields.io/badge/Email-moein.fatehi@gmail.com-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:moein.fatehi@gmail.com)

I'm the founder and managing director of [HafezSecure](https://hafezsecure.ir/en), a cybersecurity company that delivers vulnerability assessment and penetration testing, secure development, runtime protection and monitoring, and security advisory. My own focus is web, API and mobile application security: I have led vulnerability assessment and penetration testing (VAPT) teams and worked on more than 1,000 enterprise penetration testing projects as a tester, project manager and team lead. I also build open-source Burp Suite extensions and vulnerable-by-design labs, so testers find real issues faster and learners can practise safely.

## Highlights

- **1,000+ enterprise penetration tests** across web applications, APIs, Android and iOS apps, desktop software, networks and infrastructure.
- **Two extensions in PortSwigger's BApp Store:** [Backup Finder](https://portswigger.net/bappstore/466bc6cbf5bb4449b56af7bd9c0000ea) and [CVSS Calculator](https://portswigger.net/bappstore/e2209cdad8474342a695b2e279c294f0).
- **Open-source tools and training labs** starred, forked and pulled by the security community: [![GitHub stars](https://img.shields.io/github/stars/moeinfatehi?affiliations=OWNER&style=flat&logo=github&label=GitHub%20stars)](https://github.com/moeinfatehi?tab=repositories&sort=stargazers) [![GitHub followers](https://img.shields.io/github/followers/moeinfatehi?style=flat&logo=github&label=followers)](https://github.com/moeinfatehi?tab=followers)
- **CTF champion** with multiple first-place finishes as part of the DCUA team.

## Burp Suite extensions

| Extension | What it does | Install | Stars |
|---|---|---|---|
| [Backup Finder](https://github.com/moeinfatehi/Backup-Finder) | Finds backup, old, temporary and unreferenced files that leak sensitive data, using payloads generated from the target's own structure (OWASP WSTG-CONF-04) | [BApp Store](https://portswigger.net/bappstore/466bc6cbf5bb4449b56af7bd9c0000ea) | [![stars](https://img.shields.io/github/stars/moeinfatehi/Backup-Finder?style=flat&label=%E2%98%85)](https://github.com/moeinfatehi/Backup-Finder/stargazers) |
| [Admin Panel Finder](https://github.com/moeinfatehi/Admin-Panel_Finder) | Enumerates exposed admin panels and login pages with 1,000+ built-in payloads and technology-aware wordlists (OWASP WSTG-CONF-05) | [Release](https://github.com/moeinfatehi/Admin-Panel_Finder/releases) | [![stars](https://img.shields.io/github/stars/moeinfatehi/Admin-Panel_Finder?style=flat&label=%E2%98%85)](https://github.com/moeinfatehi/Admin-Panel_Finder/stargazers) |
| [PassiveDigger](https://github.com/moeinfatehi/PassiveDigger) | Passively analyses proxied traffic for SQL errors, reflected parameters, LFI hints, serialized data, weak cookie flags and missing security headers | [Release](https://github.com/moeinfatehi/PassiveDigger/releases) | [![stars](https://img.shields.io/github/stars/moeinfatehi/PassiveDigger?style=flat&label=%E2%98%85)](https://github.com/moeinfatehi/PassiveDigger/stargazers) |
| [CVSS Calculator](https://github.com/moeinfatehi/CVSS_Calculator) | Scores vulnerabilities with CVSS v2 and v3.1 offline, without leaving Burp Suite | [BApp Store](https://portswigger.net/bappstore/e2209cdad8474342a695b2e279c294f0) | [![stars](https://img.shields.io/github/stars/moeinfatehi/CVSS_Calculator?style=flat&label=%E2%98%85)](https://github.com/moeinfatehi/CVSS_Calculator/stargazers) |

## Vulnerable-by-design labs

Self-contained Docker labs for practising common web vulnerabilities and filter bypasses.

| Lab | Vulnerability class | Docker pulls |
|---|---|---|
| [XSS challenges](https://github.com/moeinfatehi/xss_vulnerability_challenges) | Cross-site scripting and XSS filter bypasses | [![pulls](https://img.shields.io/docker/pulls/moeinfatehi/xss_vulnerability_challenges?style=flat&logo=docker&label=pulls)](https://hub.docker.com/r/moeinfatehi/xss_vulnerability_challenges) |
| [File upload scenarios](https://github.com/moeinfatehi/file_upload_vulnerability_scenarios) | Unrestricted file upload and upload-filter bypasses leading to code execution | [![pulls](https://img.shields.io/docker/pulls/moeinfatehi/file_upload_vulnerabilities?style=flat&logo=docker&label=pulls)](https://hub.docker.com/r/moeinfatehi/file_upload_vulnerabilities) |
| [LFI to RCE](https://github.com/moeinfatehi/lfi-to-rce-scenario) | Local file inclusion escalated to remote code execution | [![pulls](https://img.shields.io/docker/pulls/moeinfatehi/lfi-to-rce-scenario?style=flat&logo=docker&label=pulls)](https://hub.docker.com/r/moeinfatehi/lfi-to-rce-scenario) |
| [RFI scenarios](https://github.com/moeinfatehi/rfi_vulnerability_scenarios) | Remote file inclusion, one new bypass technique per challenge | [![pulls](https://img.shields.io/docker/pulls/moeinfatehi/rfi_vulnerability_scenarios?style=flat&logo=docker&label=pulls)](https://hub.docker.com/r/moeinfatehi/rfi_vulnerability_scenarios) |
| [CAPTCHA logic bypass](https://github.com/moeinfatehi/captcha_logical_bypass_scenarios) | Broken CAPTCHA logic that re-enables brute-force attacks | [![pulls](https://img.shields.io/docker/pulls/moeinfatehi/captcha_logical_bypass_scenarios?style=flat&logo=docker&label=pulls)](https://hub.docker.com/r/moeinfatehi/captcha_logical_bypass_scenarios) |
| [DVWA behind ModSecurity](https://github.com/moeinfatehi/dvwa-modsecurity-waf) | Attacking a web app protected by a ModSecurity WAF and tuning its rules | Docker Compose (no image) |

## Courses and research

- **[Linux for Cyber Security](https://github.com/moeinfatehi/LinuxForCyberSecurityCourse):** an open course with lectures, assignments and scripts, from Linux fundamentals to boot security, firewalls, SSH and hardening.
- **[Awesome Smart Contract Security](https://github.com/moeinfatehi/Awesome-Smart-Contract-Security):** a curated guide to Solidity vulnerabilities (SWC, OWASP), audit tools, papers and courses.
- **[Cosmos Chain Security](https://github.com/moeinfatehi/CosmosChainSecurity):** a security guide for Cosmos SDK chains covering IBC, validators and DEXs, with an Osmosis case study.

## Areas of expertise

Web application and API penetration testing · Mobile application security (Android, iOS) · OWASP WSTG and Top 10 · Burp Suite extension development in Java · Vulnerability scoring and management (CVSS) · Smart contract and blockchain security · Leading security testing teams

---

Need a penetration test, secure development support or security advice? Visit [HafezSecure](https://hafezsecure.ir/en). Found a bug in one of my tools or labs? Open an issue on its repository. For anything else, reach me on [LinkedIn](https://www.linkedin.com/in/moeinfatehi).
