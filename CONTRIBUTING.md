# Contributing to OpenSecOps

## Pull requests are not accepted

External pull requests are not accepted on any OpenSecOps repository, for any change. This is policy, not friction.

OpenSecOps runs in customer accounts with admin-equivalent privilege scope: SOAR orchestrates Security Hub findings and runs auto-remediations across customer accounts; Foundation implements multi-account governance, IAM, log aggregation, and routine hygiene automation. The blast radius of a compromised release of either is comparable to that of a compromised CSPM, EDR, or SIEM. Governance therefore follows the cathedral model — a small core team curates the codebase, design and dependency decisions sit with that team, and there is one chain of accountability and one signing identity from commit to released artefact. Pull requests from outside the team are incompatible with that model and are closed without review.

The source is public under MPL-2.0 for transparency, customer verification, and security review by anyone who wants to read it. Forking under MPL-2.0 is permitted by the licence and requires no coordination with us.

## What is welcomed

**Bug reports for non-security defects** — public, accepted, and acknowledged on the standard Issues tab of the affected component repository in the [OpenSecOps-Org organisation](https://github.com/OpenSecOps-Org). Use the [bug report template](https://github.com/OpenSecOps-Org/.github/blob/main/profile/ISSUE_TEMPLATE/bug_report.md). Triage and any fix are authored by the core team; the report is the contribution. There is no implicit timeline beyond the regular release cadence.

**Vulnerability reports** — welcomed from anyone, with named credit per the coordinated-disclosure timeline in each component's `SECURITY.md`.

- *Preferred channel*: the GitHub Security Advisory ("Report a vulnerability") flow on the affected component repository in the [OpenSecOps-Org organisation](https://github.com/OpenSecOps-Org). This produces a private advisory visible only to the core team.
- *Fallback*: `info@opensecops.org`, for coordination on something that does not yet have a clear repository home.

Do not file vulnerability reports on the public Issues tab — a public issue mentioning an unpatched vulnerability is itself a disclosure event.

## Where the substance lives

- **[Trust page](https://www.opensecops.org/trust.html)** — entry point to the supply-chain artefacts, governance posture, and verification recipes.
- **Per-component `SECURITY.md`** — at the root of each repository in the [OpenSecOps-Org organisation](https://github.com/OpenSecOps-Org). Carries the supported-versions statement, the per-component acknowledged-and-deferred CVE list, the signing identity, and the CVE-response SLA (critical 3 business days, high 10, medium/low next regular release).
- **[Canonical supply-chain document](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/security/supply-chain.md)** — verification recipes, framework citations (S2C2F, SLSA, CycloneDX, CISA SSDF, CRA, ECCN), and procurement-questionnaire crosswalk.
