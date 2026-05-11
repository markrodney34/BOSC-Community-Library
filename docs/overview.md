# BOSC Community Library — Project Overview

![Status](https://img.shields.io/badge/status-active-brightgreen)
![License](https://img.shields.io/badge/license-Apache%202.0-blue)
![Contributions Welcome](https://img.shields.io/badge/contributions-welcome-orange)
![Last Updated](https://img.shields.io/badge/last%20updated-May%202026-lightgrey)

---

## Project Metadata

| Field              | Detail                                                |
|--------------------|-------------------------------------------------------|
| **Project Name**   | BOSC Community Library                                |
| **Status**         | Active — Accepting Contributions                      |
| **License**        | Apache License 2.0                                    |
| **Current Version**| v1.2.0                                                |
| **Maintained By**  | BOSC Community Maintainers                            |
| **Primary Contact**| Open an [issue](../.github/ISSUE_TEMPLATE/bug_report.md) for all queries |
| **Repository**     | https://github.com/markrodney34/BOSC-Community-Library |
| **Issue Tracker**  | https://github.com/markrodney34/BOSC-Community-Library/issues |
| **Created**        | May 2026                                              |
| **Governance**     | Community-governed, maintainer-approved PRs           |

---

## Objectives

The BOSC Community Library is a centralized, open-source repository of curated resources, tools, and documentation designed to serve the broader open-source community. Our core objectives are:

- Provide a single, verified point of reference for community contributors and learners
- Curate high-quality resources across licensing, development tools, governance, and security
- Foster inclusive participation through multilingual support and accessible documentation
- Maintain transparency through public governance, auditable commit history, and open issues

---

## Project Scope

### In Scope
- Open source learning resources and curated reading lists
- Licensing guides and legal analysis documentation
- Community governance templates (Code of Conduct, Contributing guide, Issue/PR templates)
- Localized resources for non-English-speaking communities
- A structured, machine-readable resource database (JSON format)

### Out of Scope
- Hosting or mirroring third-party software packages
- Providing legal advice (resources are for educational purposes only)
- Proprietary or closed-source tooling

---

## Architecture

```
BOSC-Community-Library/
├── .github/                    # GitHub-specific configuration
│   ├── ISSUE_TEMPLATE/         # Standardized issue templates
│   └── PULL_REQUEST_TEMPLATE.md
├── docs/                       # Project documentation
│   └── overview.md             # This file
├── resources/                  # Curated resource index
│   ├── index.md                # Human-readable resource list
│   ├── database.json           # Machine-readable resource database
│   └── localized/              # Multilingual resources
│       ├── swahili.md
│       ├── french.md
│       └── portuguese.md
├── src/                        # Source scaffolding
├── CODE_OF_CONDUCT.md          # Community behavior standards
├── CONTRIBUTING.md             # Contributor technical guide
├── LEGAL_ANALYSIS.md           # Apache 2.0 license rationale
├── SUSTAINABILITY.md           # Funding and sustainability strategy
├── CHANGELOG.md                # Version history
├── CODEOWNERS                  # Automated review assignments
├── LICENSE                     # Apache License 2.0 (full text)
└── README.md                   # Project introduction
```

---

## Version History

| Version | Date         | Summary of Changes                                      |
|---------|--------------|---------------------------------------------------------|
| v1.2.0  | May 11, 2026 | Refactor: CI readiness, CHANGELOG, CODEOWNERS added    |
| v1.1.0  | May 11, 2026 | Feature: Localized resources + JSON database            |
| v1.0.1  | May 11, 2026 | Fix: Broken links audited, metadata fields added        |
| v1.0.0  | May 6, 2026  | Initial release — governance files, templates, structure|

---

## Maintainers

| Role                  | Contact Method                                        |
|-----------------------|-------------------------------------------------------|
| Lead Maintainer       | Open a GitHub Issue (response within 48 hours)        |
| Community Moderator   | Use the [Code of Conduct](../CODE_OF_CONDUCT.md) reporting channel |
| Legal Queries         | Reference [LEGAL_ANALYSIS.md](../LEGAL_ANALYSIS.md)  |

> **Note:** This project is community-governed. All decisions are made transparently through public issues and pull requests. There are no private communication channels for project decisions.

---

## Roadmap

### Near-Term (Q2 2026)
- [ ] Add GitHub Actions CI pipeline for link validation
- [ ] Expand localized resources to 5 languages
- [ ] Publish project to the Open Source Collective for funding

### Mid-Term (Q3 2026)
- [ ] Launch a searchable web interface for the resource database
- [ ] Partner with 3 African universities for content contributions
- [ ] Apply for OpenSSF Best Practices Badge

---

*This document is maintained by the BOSC Community. To suggest improvements, open an issue using the [Feature Request template](../.github/ISSUE_TEMPLATE/feature_request.md).*
