# Security Research Catalog

Researcher: José Lomelí (`je-lv`)

Last verified: November 24, 2026

This catalog contains my published CVEs and GitHub Security Advisories. Other reserved identifiers
and affected products remain private until coordinated publication.

## Published CVEs

### DreameHome Android, cloud, and MQTT services

Technical reference: [Responsible Disclosure of DreameHome Android, Cloud, and MQTT Security Vulnerabilities](https://github.com/je-lv/dreame-security-research)

| CVE | Vulnerability | Severity |
|:--|:--|:--|
| [CVE&#8209;2026&#8209;49960](https://www.cve.org/CVERecord?id=CVE-2026-49960) | Cross-account Meari credential disclosure enabling camera-media access | Critical |
| [CVE&#8209;2026&#8209;49961](https://www.cve.org/CVERecord?id=CVE-2026-49961) | Unauthorized MQTT subscriptions disclose home maps and device telemetry | Medium |
| [CVE&#8209;2026&#8209;49962](https://www.cve.org/CVERecord?id=CVE-2026-49962) | MQTT access persists after device sharing is revoked | Medium |
| [CVE&#8209;2026&#8209;49963](https://www.cve.org/CVERecord?id=CVE-2026-49963) | Tampered React Native plugin code runs inside DreameHome | High |
| [CVE&#8209;2026&#8209;49964](https://www.cve.org/CVERecord?id=CVE-2026-49964) | Unauthorized RTC token issuance for another device's live-video channel | High |
| [CVE&#8209;2026&#8209;49965](https://www.cve.org/CVERecord?id=CVE-2026-49965) | Unauthorized camera-binding reassignment between accounts | High |

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

### EUSurvey (European Commission survey platform)

Technical reference: [Responsible Disclosure of EU Commission's EUSurvey Vulnerabilities](https://github.com/je-lv/eusurvey-security-research)

| CVE | Vulnerability | Severity |
|:--|:--|:--|
| [CVE&#8209;2026&#8209;101862](https://www.cve.org/CVERecord?id=CVE-2026-101862) | Authenticated remote code execution through survey-import path traversal | High |
| [CVE&#8209;2026&#8209;101863](https://www.cve.org/CVERecord?id=CVE-2026-101863) | Any authenticated user can take over and delete other users' surveys through bulk-change | High |
| [CVE&#8209;2026&#8209;101864](https://www.cve.org/CVERecord?id=CVE-2026-101864) | Account takeover through a password-reset link that stays valid after use | High |
| [CVE&#8209;2026&#8209;101866](https://www.cve.org/CVERecord?id=CVE-2026-101866) | Anonymous invitation-token disclosure and draft corruption through unbound draft save | High |
| [CVE&#8209;2026&#8209;101867](https://www.cve.org/CVERecord?id=CVE-2026-101867) | Authenticated contact-share disclosure and takeover through broken authorization | High |
| [CVE&#8209;2026&#8209;101868](https://www.cve.org/CVERecord?id=CVE-2026-101868) | Unauthenticated survey-response disclosure through sequential contribution IDs | High |
| [CVE&#8209;2026&#8209;101869](https://www.cve.org/CVERecord?id=CVE-2026-101869) | Unauthenticated SQL injection in public result filters leaks non-public responses | High |
| [CVE&#8209;2026&#8209;101870](https://www.cve.org/CVERecord?id=CVE-2026-101870) | Anonymous overwrite of another respondent's contribution | High |
| [CVE&#8209;2026&#8209;101871](https://www.cve.org/CVERecord?id=CVE-2026-101871) | Anonymous submission to closed surveys through an unguarded Delphi update endpoint | High |
| [CVE&#8209;2026&#8209;101872](https://www.cve.org/CVERecord?id=CVE-2026-101872) | Authenticated blind SQL injection through the dashboard sort parameter | Medium |
| [CVE&#8209;2026&#8209;101873](https://www.cve.org/CVERecord?id=CVE-2026-101873) | Stored XSS through the Delphi explanation field | Medium |
| [CVE&#8209;2026&#8209;101874](https://www.cve.org/CVERecord?id=CVE-2026-101874) | Cross-user export-name disclosure and notification suppression through export-polling IDOR | Medium |
| [CVE&#8209;2026&#8209;101876](https://www.cve.org/CVERecord?id=CVE-2026-101876) | Blind SSRF through PDF export image fetching | Medium |
| [CVE&#8209;2026&#8209;101877](https://www.cve.org/CVERecord?id=CVE-2026-101877) | Cross-survey restricted-PDF access through invitation tokens | Medium |

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
| Mealie | Cross-tenant object creation in shopping-list items and recipe comments | High | CWE-639/862 | [GHSA-qxhj-xxq3-m4w2](https://github.com/mealie-recipes/mealie/security/advisories/GHSA-qxhj-xxq3-m4w2) |
| Craft CMS | Stored XSS in the control panel through an unescaped draft name | Medium | CWE-79 | [GHSA-2rp4-x2j7-qmcc](https://github.com/craftcms/cms/security/advisories/GHSA-2rp4-x2j7-qmcc) |
