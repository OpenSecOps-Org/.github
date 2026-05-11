# Security Policy

This is the **default security policy** served by GitHub for OpenSecOps repositories that do not yet carry their own `SECURITY.md`. Repositories converted to the OpenSecOps supply-chain model carry a per-component `SECURITY.md` at the root of the repository — with the supported-versions statement, the per-component acknowledged-and-deferred CVE list, signing identities, and the project-wide CVE-response SLA (critical 3 business days, high 10, medium and low at the next regular release). When present, the per-component file takes precedence; this default applies to the rest.

## Reporting a vulnerability

- **Preferred channel**: the GitHub Security Advisory ("Report a vulnerability") flow on the affected repository in the [OpenSecOps-Org organisation](https://github.com/OpenSecOps-Org). This produces a private advisory visible only to the core team.
- **Fallback channel**: `security@opensecops.org`, for coordination on something that does not yet have a clear repository home.

Do **not** report vulnerabilities via public GitHub issues, discussions, or pull requests — a public report mentioning an unpatched vulnerability is itself a disclosure event.

Reporters receive named credit per the coordinated-disclosure timeline in each component's `SECURITY.md`. The fix is authored by the core team.

## More information

- [**Trust page**](https://www.opensecops.org/trust.html) — entry point to the supply-chain posture, governance model, and verification artefacts attached to every release.
- [**Canonical supply-chain document**](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/security/supply-chain.md) — verification recipes, framework citations (S2C2F, SLSA, CycloneDX), and procurement-questionnaire crosswalk.
- [**CONTRIBUTING.md**](https://github.com/OpenSecOps-Org/.github/blob/main/CONTRIBUTING.md) — the cathedral governance model and contribution policy.
