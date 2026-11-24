<h1 align="center">José Lomelí · <img src="https://cdn.jsdelivr.net/gh/twitter/twemoji@14.0.2/assets/svg/1f1f2-1f1fd.svg" height="28" alt="Mexico"></h1>
<p align="center"><b><code>je-lv</code></b> · Offensive Security &amp; Vulnerability Research · Penetration Tester</p>
<p align="center">
  <img src="https://img.shields.io/badge/Assigned_CVEs-70-b5185c?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Published_CVEs-39-8b5cf6?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Published_GitHub_advisories-19-e5654a?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Reserved_under_coordinated_disclosure-31-d9822b?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Cybersecurity-9_years-56b6c2?labelColor=24292f&style=flat-square">
  <a href="https://www.linkedin.com/in/je-lv/"><img src="https://img.shields.io/badge/LinkedIn-je--lv-0a66c2?logo=linkedin&logoColor=white&style=flat-square"></a>
</p>

---

### `whoami`

Offensive Security Engineer with 9 years in cybersecurity across pentesting and cyber threat intelligence. I focus on web applications, Android, infrastructure, Active Directory and IoT penetration testing. Previously, as a cyber threat intelligence specialist, I investigated phishing and malware campaigns, analyzed malware and indicators of compromise, and profiled threat actors.

**Currently:** designing agent scaffolding for AI-assisted security research (methodologies and skills that direct AI agents through web, source-code and Android/IoT research, every finding verified manually), and focusing on AI security.

---

### 🎯 Featured CVEs

Fifteen selected vulnerabilities representing my research across web applications, Android, cloud APIs,
infrastructure, and IoT products. I currently have **39 published CVEs** and **25 additional
CVEs reserved** under coordinated disclosure. Other reserved identifiers and affected products remain
private until coordinated publication.

| CVE | Project | Vulnerability | Severity |
|:--|:--|:--|:--|
| [**CVE&#8209;2026&#8209;54384**](https://www.cve.org/CVERecord?id=CVE-2026-54384) | VitaFit | Authentication bypass through forged social-login identity data | Critical |
| [**CVE&#8209;2026&#8209;54378**](https://www.cve.org/CVERecord?id=CVE-2026-54378) | VitaFit | Cloud API exposes broadly privileged AWS credentials | Critical |
| [**CVE&#8209;2026&#8209;72839**](https://www.cve.org/CVERecord?id=CVE-2026-72839) | File Browser | Self-signup users inherit server root as their scope | Critical |
| [**CVE&#8209;2026&#8209;101862**](https://www.cve.org/CVERecord?id=CVE-2026-101862) | EUSurvey | Authenticated remote code execution through survey-import path traversal | High |
| [**CVE&#8209;2026&#8209;101863**](https://www.cve.org/CVERecord?id=CVE-2026-101863) | EUSurvey | Any authenticated user can take over and delete other users' surveys through bulk-change | High |
| [**CVE&#8209;2026&#8209;101869**](https://www.cve.org/CVERecord?id=CVE-2026-101869) | EUSurvey | Unauthenticated SQL injection in public result filters leaks non-public responses | High |
| [**CVE&#8209;2026&#8209;101868**](https://www.cve.org/CVERecord?id=CVE-2026-101868) | EUSurvey | Unauthenticated survey-response disclosure through sequential contribution IDs | High |
| [**CVE&#8209;2026&#8209;62685**](https://www.cve.org/CVERecord?id=CVE-2026-62685) | File Browser | Username-normalization home-directory collision | High |
| [**CVE&#8209;2026&#8209;54910**](https://www.cve.org/CVERecord?id=CVE-2026-54910) | FileBrowser Quantum | Path traversal in subtitle handler to arbitrary file read | High |
| [**CVE&#8209;2026&#8209;116682**](https://www.cve.org/CVERecord?id=CVE-2026-116682) | FileBrowser Quantum | Symlink following escapes user scope allowing arbitrary file read outside the served directory | High |
| [**CVE&#8209;2026&#8209;54382**](https://www.cve.org/CVERecord?id=CVE-2026-54382) | VitaFit | Cognito IAM permissions allow cross-user object overwrite | High |
| [**CVE&#8209;2026&#8209;54376**](https://www.cve.org/CVERecord?id=CVE-2026-54376) | VitaFit | Fitbit token interception through Android custom-scheme hijacking | High |
| [**CVE&#8209;2026&#8209;49964**](https://www.cve.org/CVERecord?id=CVE-2026-49964) | DreameHome | Unauthorized RTC token issuance for another device's live-video channel | High |
| [**CVE&#8209;2026&#8209;49965**](https://www.cve.org/CVERecord?id=CVE-2026-49965) | DreameHome | Any authenticated account can reassign another user's camera binding | High |
| [**CVE&#8209;2026&#8209;49960**](https://www.cve.org/CVERecord?id=CVE-2026-49960) | DreameHome | Cross-account Meari credential disclosure enabling camera-media access | Medium |

[View the complete CVE and security-advisory catalog →](SECURITY-RESEARCH.md)

---

### 🔬 Security Research

| Project | Scope | Results | Publication |
|:--|:--|:--|:--|
| VitaFit | Android application, cloud API and AWS infrastructure | 12 published CVEs | [Responsible disclosure](https://github.com/je-lv/vitafit-security-research) |
| DreameHome | Android application, cloud API, MQTT and camera services | 6 published CVEs | [Responsible disclosure](https://github.com/je-lv/dreame-security-research) |
| EUSurvey | European Commission survey platform: web application, authorization, SQL injection and RCE | 14 published CVEs | [Responsible disclosure](https://github.com/je-lv/eusurvey-security-research) |
| Open-source applications | File Browser, FileBrowser Quantum, Craft CMS, Horilla HR and Mealie | 7 published CVEs and 12 additional published GHSAs | [Complete catalog](SECURITY-RESEARCH.md) |

Additional coordinated disclosures remain private while vendors complete remediation and retesting.

---

### ⏳ Featured advisories awaiting CVE

Ten selected published GitHub Security Advisories without CVE identifiers.

| Project | Vulnerability | Severity | Advisory |
|:--|:--|:--|:--|
| Horilla HR | Unauthenticated arbitrary file read, including the runtime `SECRET_KEY` | Critical | [`GHSA-62vm-69r7-p4vr`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-62vm-69r7-p4vr) |
| Horilla HR | Stored XSS leading to credential theft and account takeover | High | [`GHSA-rf47-2qgf-qq4j`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-rf47-2qgf-qq4j) |
| Horilla HR | Reporting manager can overwrite any employee's bank details and redirect salary payments | High | [`GHSA-39gq-9wwx-p8hx`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-39gq-9wwx-p8hx) |
| Horilla HR | Any employee can approve any reimbursement and set an arbitrary payout amount | High | [`GHSA-56x4-6268-vg4f`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-56x4-6268-vg4f) |
| Mealie | Cross-tenant creation of shopping-list items and recipe comments | High | [`GHSA-qxhj-xxq3-m4w2`](https://github.com/mealie-recipes/mealie/security/advisories/GHSA-qxhj-xxq3-m4w2) |
| FileBrowser Quantum | Stored XSS through a DOCX hyperlink in the document viewer | Medium | [`GHSA-9wm6-jcjh-3m8c`](https://github.com/gtsteffaniak/filebrowser/security/advisories/GHSA-9wm6-jcjh-3m8c) |
| Horilla HR | Server-side template injection on REST mail-template endpoints | Medium | [`GHSA-fphr-9vwh-crmq`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-fphr-9vwh-crmq) |
| Horilla HR | Candidate can read another candidate's uploaded documents | Medium | [`GHSA-p745-9729-g8jw`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-p745-9729-g8jw) |
| Horilla HR | Employee can delete another employee's documents | Medium | [`GHSA-x72c-5gf7-97g3`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-x72c-5gf7-97g3) |
| Craft CMS | Stored XSS through an unescaped control-panel draft name | Medium | [`GHSA-2rp4-x2j7-qmcc`](https://github.com/craftcms/cms/security/advisories/GHSA-2rp4-x2j7-qmcc) |

[View all published advisories awaiting CVE assignment →](SECURITY-RESEARCH.md#published-advisories-awaiting-cve)

---

### 🧰 Tools

| Repo | What it is |
|:--|:--|
| [agentmap](https://github.com/je-lv/agentmap) | Black-box discovery, fingerprinting and risk assessment for A2A agents and MCP servers |
| [apivolt](https://github.com/je-lv/apivolt) | Spec-driven API security testing from the command line (OpenAPI/Swagger and Postman) |
| [glassboard](https://github.com/je-lv/glassboard) | Self-hosted workspace where humans and independently run AI agents coordinate work. A shared timeline and task board show what participants have recorded, who owns each task, what is blocked, and what awaits review. |
| [releasefence](https://github.com/je-lv/releasefence) | Offline check of a source directory or ZIP for secrets and unsafe paths before you publish it. |
| [sweeper](https://github.com/je-lv/sweeper) | Black-box infrastructure and web security scanner. Orchestrates proven scanners across DNS, ports, TLS, HTTP, content and templates inside a default-deny scope, and merges their output into one Markdown and HTML report. |

---

### 🏅 Recognition

Recognized in the Dutch government's national Coordinated Vulnerability Disclosure program for a
valid security report.

---

<p align="center"><sub>Last updated 2026-11-24. Figures update as pending CVEs issue and embargoes lift.</sub></p>
