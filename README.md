

# CNCF Project Template

This [template repository][template-repo] by [CNCF SIG Contributor
Strategy][contrib-strat] helps new projects join CNCF. It provides a standardized structure and starter files to quickly set up a repository following community best practices.

By creating a copy and customizing the template, projects can focus on their unique goals instead of reinventing the wheel. Overall, it makes adopting CNCF guidelines and resources easier so projects can start strong.

## Getting Started 

To create a new project repository from this CNCF template:

1. Click **Use this template** and create a copy of this repository under your own organization.

    [![Green button that says "Use this template"](https://user-images.githubusercontent.com/1368985/95903529-e9c32f00-0d5b-11eb-8723-4369f7c9e044.png)](https://github.com/new?template_name=project-template&template_owner=cncf)

2. Remove `.github/settings.yml` - this contains configuration specific to for our repo only. You should not keep this file.

3. First, Customize every [required template](#required-templates) files and those specific to your project.

4. Remove any templates not needed.

5. Delete this top level README and rename [README-template.md](README-template.md) to README.md.

6. Update all references to `project`, `repo`, etc. Add links/badges specific to your project.

## Customizing the Template 

- ### Required Templates:

  - [LICENSE](LICENSE) - Replace with your project's license
  - [CONTRIBUTING](CONTRIBUTING.md) - Add project specific contribution guidelines
  - [README](README-template.md) - Use as starting point for your README

- Most files contain TODO comments with instructions on what needs to be changed. We recommend viewing the raw text or markdown source to see all the TODO comments.

- For example, in markdown files we use this syntax:

  `<!-- TODO: ... -->`

  to provide guidance and indicate where action is required. These TODO comments will not be visible when viewing the rendered markdown on GitHub, only in the raw text.

- Reviewing the raw files or enabling markdown rendering allows you to fully utilize the template by seeing all the customizable sections marked with TODOs.

## Contents

This project contains templates for:

- [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) - Standards for community interaction and behavior 
- [CONTRIBUTING](CONTRIBUTING.md) - Guidelines for contributing to the project
- [CONTRIBUTOR_LADDER](CONTRIBUTOR_LADDER.md) - Details on roles and responsibilities for contributors.
- [DESIGN-PROPOSALS](DESIGN-PROPOSALS.md) - Template for proposing and documenting major feature designs  
- [GOVERNANCE](GOVERNANCE.md) - Project leadership, decision-making, and governance models
- [GOVERNANCE-elections](GOVERNANCE-elections.md) - Leadership election process  
- [GOVERNANCE-maintainer](GOVERNANCE-maintainer.md) - Expectations and requirements for maintainers
- [GOVERNANCE-subprojects](GOVERNANCE-subprojects.md) - Guidelines for creating subprojects
- [LICENSE](LICENSE) - Open source license terms, Apache 2.0 by default
- [MAINTAINERS](MAINTAINERS.md) - Current project maintainers and sponsoring entities
- [README](README-template.md) - High level overview and documentation for the project
- [REVIEWING](REVIEWING.md) - Code and documentation review process
- [.github/](.github/) - GitHub community health files


Please note that the security templates may be found in the [Security TAG’s project resources folder.](https://github.com/cncf/tag-security/tree/main/project-resources)

## Getting Help

Need guidance on using these templates? Want to learn more about customizing a specific template?

Check out the [How-To Guides](https://contribute.cncf.io/maintainers/templates/#how-to-guides) on our website.

The guides provide step-by-step instructions to help you:

Adopt the templates for your project

Understand what each template contains

Make customizations for your specific needs

Review the [How-To Guides](https://contribute.cncf.io/maintainers/templates/#how-to-guides) for assistance with getting started and fully utilizing these project templates.

[template-repo]: https://github.com/cncf/project-template
[contrib-strat]: https://github.com/cncf/sig-contributor-strategy/blob/master/README.md

Note: This is the README file for the templates repo. Please use [README-template.md](README-template.md) as a template for your project README.