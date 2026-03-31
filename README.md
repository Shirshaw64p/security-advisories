# Security Advisories

Independent vulnerability disclosures and technical security research involving real-world software systems.

## Advisory Portfolio

| Advisory ID | Vendor | Vulnerability Type | Status | Year |
|-------------|--------|--------------------|--------|------|
| CVE-2026-32612 | Statamic CMS | Stored Cross-Site Scripting (XSS) | Disclosed – Patched | 2026 |
| Pending | OWASP Nettacker | Security Vulnerability | Report Accepted – Under Review | 2026 |
| Pending | Drupal CMS | Security Vulnerability | Patch Pending | 2026 |
| CVE-2026-21631 | Joomla CMS | Stored Cross-Site Scripting (XSS) | Disclosed - Patched | 2026 |
| Pending | OpenPGP.js | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| Pending | Piranha CMS | Security Vulnerability | Patch Pending | 2026 |
| Pending | LangChain Core | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| Pending | BeyondTrust - Terraform Provider SRA | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| Pending | Facebook (ZSTD) | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| Pending | Strapi | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| No ID Issued - Vulnerability in unreleased version | CKAN | Security Vulnerability | Patch Pending - Public PR Credit confirmed (https://github.com/ckan/ckan/pull/9297) | 2026 |
| No ID Issued - Bug Fix | SFTPGo | Security Vulnerability | Patched - Public PR Credit confirmed | 2026 |
| Pending | Gogs | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |
| Pending | Vite | Security Vulnerability | Reported - Awaiting Vendor Response | 2026 |

---

## Overview

This repository documents vulnerability discoveries, technical analyses, and coordinated responsible disclosure work across multiple software platforms.

The objective of this work is to identify security weaknesses, analyze their technical root causes, and contribute to improving software security through responsible engagement with maintainers and the broader security ecosystem.

Rather than treating findings as isolated reports, this repository organizes advisories as part of an ongoing body of vulnerability research focused on secure engineering practices, defensive design, and product security.

---

## Research Focus Areas

Current research interests include:

- Application Security
- Product Security Engineering
- Vulnerability Discovery
- Secure Software Development Practices
- Backend Trust Boundary Analysis
- Injection Vulnerabilities
- Output Encoding Failures
- Security Architecture Review
- Responsible Disclosure Workflows

---

## Research Methodology

Security advisories documented here typically follow a structured research workflow:

1. Component and attack surface analysis  
2. Manual code inspection  
3. Source-to-sink data flow tracing  
4. Security boundary evaluation  
5. Controlled runtime validation  
6. Root cause identification  
7. Remediation analysis  
8. Coordinated disclosure with maintainers  

This approach emphasizes technical rigor, reproducibility, and meaningful security impact.

---

## Repository Structure

    security-advisories/
    │
    ├── CVE-XXXX-XXXXX/
    │   ├── README.md
    |   |── SECURITY-REPORT.md
    |   ├── TECHNICAL-ANALYSIS.md
    |   ├── IMPACT.md
    |   ├── REMEDIATION.md
    |   ├── DISCLOSURE-TIMELINE.md
    |   ├── LEARNINGS.md
    |   └── REFERENCES.md
    │
    └── advisory-index.md

---

## Advisory Portfolio

Each advisory may contain:

- Technical root cause analysis
- Vulnerability classification
- Security impact evaluation
- Reproduction methodology
- Remediation recommendations
- Disclosure timeline
- Maintainer coordination notes

Technical details may remain limited until vendors complete remediation and public disclosure becomes appropriate.

---

## Disclosure Model

All findings follow coordinated responsible disclosure practices.

Information may remain restricted until:

- Vendor remediation is completed
- Disclosure is safe and appropriate
- CVE identifiers are assigned
- Public security advisories are released

---

## Research Direction

This repository is intended to evolve into a structured record of:

- Security advisories
- Vulnerability research
- Technical analyses
- Disclosure outcomes
- Secure engineering observations

Over time this repository will document continued work in vulnerability discovery and product security analysis.

---

## Ethical Research Statement

All work documented here is conducted for defensive security improvement and ecosystem benefit. Testing is performed in controlled environments using non-destructive techniques and responsible disclosure standards.

---

## Maintainer Note

If you are a maintainer and require clarification regarding any advisory, I am available to provide additional technical details where appropriate under responsible disclosure practices.
