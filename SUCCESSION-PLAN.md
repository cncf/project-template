# Succession Plan Template

[Instructions](https://contribute.cncf.io/maintainers/templates/)

<!-- template begins here -->

# [TODO: PROJECTNAME] Succession Plan

This document describes what happens if the primary maintainer organization exits the project, or if key individuals become unavailable. The goal is to ensure the project can continue operating — releasing, responding to security issues, and governing itself — without depending on any single company or person.

## Key Roles and Backup Coverage

<!-- TODO: Fill in the names and backup contacts for each critical function. Ideally, primary and backup are from different organizations. -->

| Function | Primary | Backup | Notes |
| -------- | ------- | ------ | ----- |
| **Release management** | | | Who can create and publish releases |
| **Security response** | | | Who triages and coordinates vulnerability fixes. See [SECURITY-RESPONSE-TEAM.md](./SECURITY-RESPONSE-TEAM.md) |
| **Infrastructure credentials** | | | Who holds access to CI/CD, container registries, package repositories, DNS |
| **CNCF liaison** | | | Who communicates with the CNCF on behalf of the project |
| **Code of Conduct response** | | | Who handles CoC reports |
| **Website and documentation** | | | Who can update the project website and docs |

## Infrastructure Inventory

<!-- TODO: List all infrastructure the project depends on and who controls access. This ensures no single departure creates an access crisis. -->

| Asset | Location | Access Holders | Owner Org |
| ----- | -------- | -------------- | --------- |
| Container registry | | | |
| CI/CD system | | | |
| Package repository (PyPI, npm, etc.) | | | |
| DNS / domain | | | |
| Cloud accounts | | | |
| Signing keys | | | |
| Social media accounts | | | |
| Mailing lists | | | |

## Scenario: Primary Organization Exits

If the organization that currently provides the majority of maintainers reduces or ends its involvement:

1. **Governance continuity** — [TODO: Describe how governance decisions continue. If you have a steering committee with org caps, this is already addressed. If governance is a maintainer council, describe how remaining maintainers take over.]

2. **Release continuity** — [TODO: Describe who takes over the release process. Are release credentials held by individuals or by the project? Can releases be made without the departing org's infrastructure?]

3. **Security response continuity** — [TODO: Describe how security reports continue to be triaged. Is the security contact a project email or a company email? See SECURITY-RESPONSE-TEAM.md.]

4. **Community continuity** — [TODO: Describe how community meetings, Slack channels, and communication continue. Are these on project-owned or company-owned infrastructure?]

## Scenario: Key Individual Unavailable

If a maintainer with unique access or knowledge becomes unavailable:

1. **Bus factor mitigation** — No single person should be the only one who can perform any critical function. The table above should have at least one backup for every primary.

2. **Knowledge transfer** — [TODO: Describe how institutional knowledge is documented. Architecture decisions, release procedures, and operational runbooks should be in the repository, not in someone's head.]

3. **Credential rotation** — [TODO: Describe the process for rotating credentials if a key holder departs. Include timeline targets.]

## Review Cadence

This succession plan should be reviewed [TODO: annually / semi-annually] by the [TODO: Maintainer Council / Steering Committee] to ensure:

- All backup contacts are current and have tested their access
- Infrastructure inventory is accurate
- No single organization controls all critical functions

## References

- [GOVERNANCE.md](./GOVERNANCE.md)
- [MAINTAINERS.md](./MAINTAINERS.md)
- [SECURITY-RESPONSE-TEAM.md](./SECURITY-RESPONSE-TEAM.md)
- [CNCF Governance Best Practices](https://github.com/cncf/toc/blob/main/process/governance-best-practices.md)
