<h1 align="center">Jose Lomeli</h1>
<p align="center"><b><code>je-lv</code></b> · Offensive Security &amp; Vulnerability Research · Penetration Tester</p>
<p align="center">
  <img src="https://img.shields.io/badge/Assigned_CVEs-64-b5185c?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Published_GitHub_advisories-18-e5654a?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Reserved_under_coordinated_disclosure-58-d9822b?labelColor=24292f&style=flat-square">
  <img src="https://img.shields.io/badge/Cybersecurity-8_years-56b6c2?labelColor=24292f&style=flat-square">
  <a href="https://www.linkedin.com/in/je-lv/"><img src="https://img.shields.io/badge/LinkedIn-je--lv-0a66c2?logo=linkedin&logoColor=white&style=flat-square"></a>
</p>

---

### `whoami`

Offensive Security Engineer with 8 years in cybersecurity across pentesting and cyber threat intelligence. I focus on web applications, Android, infrastructure, Active Directory and IoT penetration testing. Previously, as a cyber threat intelligence specialist, I investigated phishing and malware campaigns, analyzed malware and indicators of compromise, and profiled threat actors.

**Currently:** designing agent scaffolding for AI-assisted security research (methodologies and skills that direct AI agents through web, source-code and Android/IoT research, every finding verified manually), and focusing on AI security.

---

### 🎯 Assigned CVEs (64)

**6 public** (below) · **58 reserved** via the VulnCheck CNA under coordinated disclosure across
consumer-IoT, health, public-sector and connected-product platforms. Reserved IDs and details are
withheld until each vendor publishes, and are added here as they do.

| CVE | Project | Vulnerability | Severity | Advisory |
|:--|:--|:--|:--|:--|
| [**CVE-2026-72839**](https://www.cve.org/CVERecord?id=CVE-2026-72839) | `filebrowser/filebrowser` | Self-signup users inherit server root as their scope | Critical | [`GHSA-6759-996p-gpj6`](https://github.com/filebrowser/filebrowser/security/advisories/GHSA-6759-996p-gpj6) |
| [**CVE-2026-62685**](https://www.cve.org/CVERecord?id=CVE-2026-62685) | `filebrowser/filebrowser` | Username-normalization home-directory collision | High | [`GHSA-7rc3-g7h6-22m7`](https://github.com/filebrowser/filebrowser/security/advisories/GHSA-7rc3-g7h6-22m7) |
| [**CVE-2026-54910**](https://www.cve.org/CVERecord?id=CVE-2026-54910) | `gtsteffaniak/filebrowser` | Path traversal in subtitle handler to arbitrary file read | High | [`GHSA-vvp7-h4fj-m28w`](https://github.com/gtsteffaniak/filebrowser/security/advisories/GHSA-vvp7-h4fj-m28w) |
| [**CVE-2026-62843**](https://www.cve.org/CVERecord?id=CVE-2026-62843) | `filebrowser/filebrowser` | Archive builder backslash handling enables zip-slip path traversal | Medium | [`GHSA-83xp-526h-j3ww`](https://github.com/filebrowser/filebrowser/security/advisories/GHSA-83xp-526h-j3ww) |
| [**CVE-2026-72779**](https://www.cve.org/CVERecord?id=CVE-2026-72779) | `craftcms/cms` | Arbitrary file read via SplFileObject in non-sandboxed template contexts | Medium | [`GHSA-957r-qf9p-67xw`](https://github.com/craftcms/cms/security/advisories/GHSA-957r-qf9p-67xw) |
| [**CVE-2026-62684**](https://www.cve.org/CVERecord?id=CVE-2026-62684) | `filebrowser/filebrowser` | Share API exposes the password hash and bypass token | Low | [`GHSA-833g-cqhp-h72j`](https://github.com/filebrowser/filebrowser/security/advisories/GHSA-833g-cqhp-h72j) |

---

### ⏳ Published advisories, CVE pending (12)

These advisories are published and credit-accepted on GitHub; a CVE was requested for each and
assignment is in progress.

| Project | Vulnerability | Severity | CWE | Advisory |
|:--|:--|:--|:--|:--|
| `horilla/horilla-hr` | Unauthenticated arbitrary file read under the media root | Critical | CWE-22/284 | [`GHSA-62vm-69r7-p4vr`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-62vm-69r7-p4vr) |
| `horilla/horilla-hr` | Stored XSS leading to credential theft and account takeover | High | CWE-79/862 | [`GHSA-rf47-2qgf-qq4j`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-rf47-2qgf-qq4j) |
| `horilla/horilla-hr` | Any employee can approve any reimbursement for an arbitrary amount | High | CWE-639/862 | [`GHSA-56x4-6268-vg4f`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-56x4-6268-vg4f) |
| `horilla/horilla-hr` | Reporting manager can overwrite any employee's bank details | High | CWE-639/862 | [`GHSA-39gq-9wwx-p8hx`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-39gq-9wwx-p8hx) |
| `gtsteffaniak/filebrowser` | Symlink following escapes user scope to arbitrary file read | High | CWE-22/59 | [`GHSA-mgqf-5mf5-prfj`](https://github.com/gtsteffaniak/filebrowser/security/advisories/GHSA-mgqf-5mf5-prfj) |
| `horilla/horilla-hr` | Server-side template injection on REST mail-template endpoints | Medium | CWE-1336 | [`GHSA-fphr-9vwh-crmq`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-fphr-9vwh-crmq) |
| `horilla/horilla-hr` | Candidate can read any other candidate's uploaded documents | Medium | CWE-639 | [`GHSA-p745-9729-g8jw`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-p745-9729-g8jw) |
| `horilla/horilla-hr` | Candidate can write notes on any other candidate's hiring record | Medium | CWE-639/862 | [`GHSA-v963-hrfx-34mw`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-v963-hrfx-34mw) |
| `horilla/horilla-hr` | Employee can delete any other employee's documents | Medium | CWE-639/862 | [`GHSA-x72c-5gf7-97g3`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-x72c-5gf7-97g3) |
| `horilla/horilla-hr` | Manager of one person can self-approve a leave allocation | Medium | CWE-639/863 | [`GHSA-gc35-jfv9-r3cm`](https://github.com/horilla/horilla-hr/security/advisories/GHSA-gc35-jfv9-r3cm) |
| `gtsteffaniak/filebrowser` | Stored XSS via DOCX hyperlink in the document viewer | Medium | CWE-79 | [`GHSA-9wm6-jcjh-3m8c`](https://github.com/gtsteffaniak/filebrowser/security/advisories/GHSA-9wm6-jcjh-3m8c) |
| `craftcms/cms` | Stored XSS in the control panel via unescaped draft name | Medium | CWE-79 | [`GHSA-2rp4-x2j7-qmcc`](https://github.com/craftcms/cms/security/advisories/GHSA-2rp4-x2j7-qmcc) |

---

### 🧰 Tools

| Repo | What it is |
|:--|:--|
| [agentmap](https://github.com/je-lv/agentmap) | Black-box discovery, fingerprinting and risk assessment for A2A agents and MCP servers |
| [apivolt](https://github.com/je-lv/apivolt) | Spec-driven API security testing from the command line (OpenAPI/Swagger and Postman) |
| [glassboard](https://github.com/je-lv/glassboard) | Self-hosted workspace where humans and independently run AI agents coordinate work. A shared timeline and task board show what participants have recorded, who owns each task, what is blocked, and what awaits review. |

---

### 🏅 Recognition

Recognized in the Dutch government's national Coordinated Vulnerability Disclosure program for a
valid security report.

---

<p align="center"><sub>Counts verified against GitHub's advisory API on 2026-10-12. Figures update as pending CVEs issue and embargoes lift.</sub></p>
