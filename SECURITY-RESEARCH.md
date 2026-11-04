# Security Research Catalog

Researcher: Jose Lomeli (`je-lv`)

Last verified: November 5, 2026

This catalog contains my published CVEs and GitHub Security Advisories. Reserved identifiers and
affected products remain private until coordinated publication.

## Published CVEs

### VitaFit Android and cloud services

Technical reference: [Responsible Disclosure of VitaFit Android and Cloud Security Vulnerabilities](https://github.com/je-lv/vitafit-security-research)

| CVE | Vulnerability | Severity |
|:--|:--|:--|
| [CVE&#8209;2026&#8209;54372](https://www.cve.org/CVERecord?id=CVE-2026-54372) | Insecure TLS certificate validation | High |
| [CVE&#8209;2026&#8209;54373](https://www.cve.org/CVERecord?id=CVE-2026-54373) | Cleartext traffic through missing network security configuration | Low |
| [CVE&#8209;2026&#8209;54374](https://www.cve.org/CVERecord?id=CVE-2026-54374) | Hardcoded third-party credentials | High |
| [CVE&#8209;2026&#8209;54375](https://www.cve.org/CVERecord?id=CVE-2026-54375) | Long-lived session-token exposure | High |
| [CVE&#8209;2026&#8209;54376](https://www.cve.org/CVERecord?id=CVE-2026-54376) | Fitbit token interception through Android custom-scheme hijacking | High |
| [CVE&#8209;2026&#8209;54377](https://www.cve.org/CVERecord?id=CVE-2026-54377) | Cross-account health and profile data access through IDOR | Medium |
| [CVE&#8209;2026&#8209;54378](https://www.cve.org/CVERecord?id=CVE-2026-54378) | Cloud API exposes broadly privileged AWS credentials | Critical |
| [CVE&#8209;2026&#8209;54380](https://www.cve.org/CVERecord?id=CVE-2026-54380) | Stored XSS through SVG file upload | Medium |
| [CVE&#8209;2026&#8209;54381](https://www.cve.org/CVERecord?id=CVE-2026-54381) | Unauthenticated access to a shared cloud-storage bucket | High |
| [CVE&#8209;2026&#8209;54382](https://www.cve.org/CVERecord?id=CVE-2026-54382) | Cognito IAM permissions allow cross-user object overwrite | High |
| [CVE&#8209;2026&#8209;54383](https://www.cve.org/CVERecord?id=CVE-2026-54383) | Excessive user-data exposure through the relation search endpoint | Medium |
| [CVE&#8209;2026&#8209;54384](https://www.cve.org/CVERecord?id=CVE-2026-54384) | Authentication bypass through forged social-login identity data | Critical |

### Open-source applications

| CVE | Project | Vulnerability | Severity |
|:--|:--|:--|:--|
| [CVE&#8209;2026&#8209;72839](https://www.cve.org/CVERecord?id=CVE-2026-72839) | File Browser | Self-signup users inherit server root as their scope | Critical |
| [CVE&#8209;2026&#8209;62685](https://www.cve.org/CVERecord?id=CVE-2026-62685) | File Browser | Username-normalization home-directory collision | High |
| [CVE&#8209;2026&#8209;54910](https://www.cve.org/CVERecord?id=CVE-2026-54910) | FileBrowser Quantum | Subtitle-handler path traversal to arbitrary file read | High |
| [CVE&#8209;2026&#8209;116682](https://www.cve.org/CVERecord?id=CVE-2026-116682) | FileBrowser Quantum | Symlink following escapes the served-directory boundary | High |
| [CVE&#8209;2026&#8209;62843](https://www.cve.org/CVERecord?id=CVE-2026-62843) | File Browser | Archive builder backslash handling enables zip-slip path traversal | Medium |
| [CVE&#8209;2026&#8209;72779](https://www.cve.org/CVERecord?id=CVE-2026-72779) | Craft CMS | Arbitrary file read through `SplFileObject` in non-sandboxed template contexts | Medium |
| [CVE&#8209;2026&#8209;62684](https://www.cve.org/CVERecord?id=CVE-2026-62684) | File Browser | Share API exposes the password hash and bypass token | Low |

## Published advisories awaiting CVE

| Project | Vulnerability | Severity | CWE | Advisory |
|:--|:--|:--|:--|:--|
| Horilla HR | Unauthenticated arbitrary file read under the media root, including the runtime `SECRET_KEY` | Critical | CWE-22/284 | [GHSA-62vm-69r7-p4vr](https://github.com/horilla/horilla-hr/security/advisories/GHSA-62vm-69r7-p4vr) |
| Horilla HR | Stored XSS leading to credential theft and account takeover | High | CWE-79/862 | [GHSA-rf47-2qgf-qq4j](https://github.com/horilla/horilla-hr/security/advisories/GHSA-rf47-2qgf-qq4j) |
| Horilla HR | Any employee can approve any reimbursement and set an arbitrary payout amount | High | CWE-639/862 | [GHSA-56x4-6268-vg4f](https://github.com/horilla/horilla-hr/security/advisories/GHSA-56x4-6268-vg4f) |
| Horilla HR | Reporting manager can overwrite any employee's bank details and redirect salary payments | High | CWE-639/862 | [GHSA-39gq-9wwx-p8hx](https://github.com/horilla/horilla-hr/security/advisories/GHSA-39gq-9wwx-p8hx) |
| Horilla HR | Server-side template injection on REST mail-template endpoints | Medium | CWE-1336 | [GHSA-fphr-9vwh-crmq](https://github.com/horilla/horilla-hr/security/advisories/GHSA-fphr-9vwh-crmq) |
| Horilla HR | Candidate can read any other candidate's uploaded documents | Medium | CWE-639 | [GHSA-p745-9729-g8jw](https://github.com/horilla/horilla-hr/security/advisories/GHSA-p745-9729-g8jw) |
| Horilla HR | Candidate can write notes on any other candidate's hiring record | Medium | CWE-639/862 | [GHSA-v963-hrfx-34mw](https://github.com/horilla/horilla-hr/security/advisories/GHSA-v963-hrfx-34mw) |
| Horilla HR | Employee can delete any other employee's documents | Medium | CWE-639/862 | [GHSA-x72c-5gf7-97g3](https://github.com/horilla/horilla-hr/security/advisories/GHSA-x72c-5gf7-97g3) |
| Horilla HR | Manager of one person can self-approve a leave allocation | Medium | CWE-639/863 | [GHSA-gc35-jfv9-r3cm](https://github.com/horilla/horilla-hr/security/advisories/GHSA-gc35-jfv9-r3cm) |
| FileBrowser Quantum | Stored XSS through a DOCX hyperlink in the document viewer | Medium | CWE-79 | [GHSA-9wm6-jcjh-3m8c](https://github.com/gtsteffaniak/filebrowser/security/advisories/GHSA-9wm6-jcjh-3m8c) |
| Craft CMS | Stored XSS in the control panel through an unescaped draft name | Medium | CWE-79 | [GHSA-2rp4-x2j7-qmcc](https://github.com/craftcms/cms/security/advisories/GHSA-2rp4-x2j7-qmcc) |
