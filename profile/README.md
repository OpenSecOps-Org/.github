# OpenSecOps - AWS Security Automation Platform

Welcome to OpenSecOps! This platform provides enterprise-grade security automation for AWS environments through two main products: Foundation and SOAR. Some components have been open-source for a long time and can be used stand-alone. 

All products have passed stringent AWS Foundational Technical Reviews and are battle-tested and in active use in the industry.

## Products

### Foundation
**Cloud infrastructure foundation** implementing AWS best practices with features including:
- AWS Control Tower integration
- Centralized logging and archival
- Text-based AWS configuration management
- Single Sign-On (SSO) with multi-factor authentication
- Just-In-Time (JIT) elevated access management

### SOAR (Security Orchestration, Automation, and Response)
**Security automation platform** with serverless architecture including:
- AWS Security Hub integration
- Automated incident response with predefined playbooks
- Forensic analysis capabilities
- Ticketing system integration (Jira, ServiceNow)
- AI-powered security reporting

## Getting Started

To install OpenSecOps, clone the [Installer repository](https://github.com/OpenSecOps-Org/Installer) and follow the instructions in its README.

## Documentation

Comprehensive documentation is available in the [Documentation repository](https://github.com/OpenSecOps-Org/Documentation), including:

### Foundation Documentation
- [Installation Manual](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/Foundation/OpenSecOps%20Foundation%20Installation%20Manual.docx.pdf) - Complete deployment guide
- [Technical Design Specification](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/Foundation/OpenSecOps%20Foundation%20TDS.docx.pdf) - Architecture details
- [Standard Operating Procedures](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/Foundation/OpenSecOps%20Foundation%20Account%20Properties%20SOP.docx.pdf) - Day-to-day management

### SOAR Documentation
- [Installation Manual](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20-%20Installation%20Manual.docx.pdf) - Step-by-step deployment
- [Technical Design Specification](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20-%20TDS.docx.pdf) - Architecture and design
- [Standard Operating Procedures](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20-%20SOP.docx.pdf) - Operational tasks
- Component-specific SOPs:
  - [DynamoDB Tables SOP](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20DynamoDB%20Tables%20-%20SOP.docx.pdf)
  - [KMS Keys SOP](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20KMS%20Keys%20-%20SOP.docx.pdf)
  - [S3 Buckets SOP](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/SOAR/OpenSecOps%20SOAR%20S3%20Buckets%20-%20SOP.docx.pdf)

## Governance and contribution

OpenSecOps is open source under MPL-2.0. The contribution model is a cathedral, not a bazaar: a small core team curates the codebase, and external pull requests are not accepted on any repository. The [Trust page](https://www.opensecops.org/trust.html) explains why; [CONTRIBUTING.md](https://github.com/OpenSecOps-Org/.github/blob/main/CONTRIBUTING.md) covers the operational details.

What is welcomed:

- **Bug reports for non-security defects** — public, accepted, and acknowledged. Use the [bug report template](https://github.com/OpenSecOps-Org/.github/blob/main/ISSUE_TEMPLATE/bug_report.md) on the affected component repository.
- **Vulnerability reports** — via the GitHub Security Advisory flow ("Report a vulnerability") on the affected repository. Fallback channel: `security@opensecops.org`. Reporters receive named credit per the coordinated-disclosure timeline in each component's `SECURITY.md`.
- **Forking under MPL-2.0** — permitted by the licence; no coordination needed.

Reference documents (all in the [`OpenSecOps-Org/.github`](https://github.com/OpenSecOps-Org/.github) special repository):

- [CONTRIBUTING.md](https://github.com/OpenSecOps-Org/.github/blob/main/CONTRIBUTING.md) — full policy and rationale.
- [CODE_OF_CONDUCT.md](https://github.com/OpenSecOps-Org/.github/blob/main/CODE_OF_CONDUCT.md) — community standards.
- [SECURITY.md](https://github.com/OpenSecOps-Org/.github/blob/main/SECURITY.md) — vulnerability disclosure policy.

## Website

Visit our website at [https://opensecops.org](https://opensecops.org) for product information and stakeholder-focused material. The [Trust page](https://www.opensecops.org/trust.html) is the entry point to the supply-chain posture, governance model, and verification artefacts attached to every release.

## Mailing List

The OpenSecOps newsletter provides updates on our open-source AWS security and operations platform. Subscribe to receive announcements about new features, security best practices, implementation tips, and community contributions. We'll share insights about both our Foundation (AWS infrastructure best practices) and SOAR (security automation) components, along with practical guidance for deploying and managing secure cloud environments. This low-volume newsletter helps you stay informed about this project that reduces AWS setup from person-years to just days.

[https://buttondown.com/opensecops](https://buttondown.com/opensecops)
