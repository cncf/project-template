# Project Governance

Because project governance varies widely, we offer several templates covering
common systems of governance used by various CNCF projects.  In order to
adopt them, choose the one closest to how you want your project to be governed,
then rename the appropriate `GOVERNANCE-xxx.md` file to GOVERNANCE.md,
overwriting this file, and customize it.  

See the Contributor Strategy document on [Leadership Selection](https://contribute.cncf.io/maintainers/governance/leadership-selection/)
for more background.  Please also review [SustainOSS's Governance Readiness Checklist](https://sustainers.github.io/governance-readiness/)
as preparation for making governance decisions.

## Governance Templates Supplied

`GOVERNANCE-maintainer.md` supplies rules for a simple self-selecting council
of Maintainers as project governance.  It assumes that there is no distinction
between the contributors who create the majority of code and documentation for
the project and the group who makes all decisions for the project.  This
governance is suitable for small, very unified projects, and is often a good
starting point for project governance.  It is based on the Jaeger project's
governance.

`GOVERNANCE-elections.md` is a template for an elected steering committee,
where senior leadership is elected by the body of contributors.  This is a
suitable structure for larger projects with an established community.  The
template is based on Kubernetes project governance.

`GOVERNANCE-subprojects.md` is a template for a "project of projects" where
the CNCF project is more of an umbrella for a bunch of closely related
subprojects.  It is based on Konveyor project governance.
