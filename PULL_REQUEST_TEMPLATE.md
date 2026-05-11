# Pull requests are not accepted on OpenSecOps repositories

External pull requests are not accepted on any OpenSecOps repository, for any change. The full reasoning is in [CONTRIBUTING.md](https://github.com/OpenSecOps-Org/.github/blob/main/profile/CONTRIBUTING.md) — in short: OpenSecOps runs in customer accounts with admin-equivalent privilege scope, and governance follows the cathedral model with one chain of accountability and one signing identity per release.

**This PR will be closed without review.** If you opened it because you wanted to:

- **Report a bug (non-security)** — please open an issue on the affected component repository instead, using the [bug report template](https://github.com/OpenSecOps-Org/.github/blob/main/profile/ISSUE_TEMPLATE/bug_report.md). Public, accepted, and acknowledged.
- **Report a vulnerability** — please use the GitHub Security Advisory flow ("Report a vulnerability") on the affected component repository in the [OpenSecOps-Org organisation](https://github.com/OpenSecOps-Org), not a public PR or issue. A public report of an unpatched vulnerability is itself a disclosure event. Fallback channel: `info@opensecops.org`. Reporters receive named credit per the coordinated-disclosure timeline in each component's `SECURITY.md`.
- **Fork and modify the code for your own use** — that is permitted by the MPL-2.0 licence and requires no coordination with us. No PR is needed.

For the substantive supply-chain posture, signing identities, and verification artefacts attached to every release, see the [Trust page](https://www.opensecops.org/trust.html), each component's `SECURITY.md`, and the [canonical supply-chain document](https://github.com/OpenSecOps-Org/Documentation/blob/main/docs/security/supply-chain.md).
