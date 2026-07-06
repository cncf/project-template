# Security Response Team Template

[Instructions](https://contribute.cncf.io/maintainers/templates/)

<!-- template begins here -->

# [TODO: PROJECTNAME] Security Response Team

The Security Response Team (SRT) is responsible for handling all reports of security vulnerabilities in [TODO: PROJECTNAME]. The team triages, evaluates, coordinates fixes, and manages disclosure for reported security issues.

## Members

SRT membership should include individuals from more than one organization where possible, to ensure continuity if any single organization reduces its involvement.

| Name | GitHub | Company | Role | Term |
| ---- | ------ | ------- | ---- | ---- |
|      |        |         | Lead |      |
|      |        |         | Member |    |
|      |        |         | Member |    |

<!-- TODO: Populate with at least 2 members. The team should be large enough to ensure coverage across time zones and availability, but small enough that confidential information is appropriately contained. 3-5 members is typical. -->

## Responsibilities

- **Triage** incoming security reports within [TODO: Number, suggested: 3] business days of receipt
- **Evaluate** severity and impact using a documented methodology (e.g., CVSS)
- **Coordinate** fixes with maintainers, ensuring patches are developed and tested before disclosure
- **Manage disclosure** through [GitHub Security Advisories](https://docs.github.com/en/code-security/security-advisories) or equivalent coordinated disclosure process
- **Communicate** with reporters, keeping them informed of progress and expected timelines
- **Publish** advisories and notify the community through documented channels
- **Review** and update this document and the project's [SECURITY.md](./SECURITY.md) at least annually

## Reporting

Security vulnerabilities should be reported to:

<!-- TODO: Choose one or more of the following reporting mechanisms -->

- **GitHub Security Advisories:** [TODO: Link to project security advisories page]
- **Email:** [TODO: security@projectname.io] (reaches all SRT members)
- **GPG:** Available on request from SRT members

Do **not** report security vulnerabilities through public GitHub issues.

## Response Process

1. **Acknowledgment** — SRT acknowledges receipt within [TODO: Number, suggested: 3] business days
2. **Triage** — SRT evaluates severity and determines if the report is valid within [TODO: Number, suggested: 7] business days
3. **Fix development** — SRT coordinates with maintainers to develop a fix. Timeline depends on severity:
   - **Critical/High:** Target fix within [TODO: Number, suggested: 14] days
   - **Medium/Low:** Target fix within [TODO: Number, suggested: 30] days
4. **Disclosure** — Coordinated disclosure via GitHub Security Advisory. Reporter is credited unless they request anonymity.
5. **Post-incident** — SRT reviews the response process and updates procedures if needed.

## Membership Changes

- **Adding members:** Any current SRT member may nominate a candidate. Approval requires consensus of existing SRT members.
- **Removing members:** Members may step down at any time. Members inactive for [TODO: Number, suggested: 6] months may be removed by consensus of remaining members.
- **Annual review:** The SRT roster is reviewed at least once per year by the [TODO: Maintainer Council / Steering Committee] to ensure adequate coverage and organizational diversity.

## Confidentiality

SRT members must maintain confidentiality of reported vulnerabilities until coordinated disclosure. Sharing vulnerability details outside the SRT without reporter consent is a violation of this policy and the project's [Code of Conduct](./CODE_OF_CONDUCT.md).

## References

- [SECURITY.md](./SECURITY.md) — public-facing security policy and reporting instructions
- [Kubernetes Security Response Committee](https://github.com/kubernetes/committee-security-response) — reference model
- [CNCF Governance Best Practices](https://github.com/cncf/toc/blob/main/process/governance-best-practices.md)
