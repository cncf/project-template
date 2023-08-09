

# CNCF Project Template

This repository serves as a [project template][template-repo] created by [CNCF SIG Contributor
Strategy][contrib-strat] that new open source projects can use when joining the Cloud Native Computing Foundation (CNCF). The template provides a standardized structure and initial files to help projects quickly set up a repository that follows community best practices. By forking and customizing this template, new CNCF projects can avoid reinventing the wheel and instead focus on their unique goals and needs. Overall, the template makes it easier for projects to get started under the CNCF with recommended guidelines and resources already in place.. It contains template files and best practices to help projects quickly adopt processes that align with CNCF standards.


## Getting Started 

To create a new project repository from this CNCF template:

1. Click **Use this template** and create a copy of this repository under your own organization.

    [![Green button that says "Use this template"](https://user-images.githubusercontent.com/1368985/95903529-e9c32f00-0d5b-11eb-8723-4369f7c9e044.png)](https://github.com/new?template_name=project-template&template_owner=cncf)

2. Remove `.github/settings.yml` - this contains configuration specific to for our repo only. You should not keep this file.

3. First, Customize every [required template](#required-templates) files and those specific to your project..

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

- [LICENSE](LICENSE) - Apache 2.0 by default
- [CONTRIBUTING](CONTRIBUTING.md) - Contribution guidelines
- [README](README-template.md) - Project overview and help 
- [GOVERNANCE](GOVERNANCE.md) - Project leadership and governance 
- [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md) - Community code of conduct
- [CONTRIBUTOR_LADDER](CONTRIBUTOR_LADDER.md)
- [+-DESIGN-PROPOSALS.md DESIGN-PROPOSALS.md
- GOVERNANCE-elections.md GOVERNANCE-elections.md
- GOVERNANCE-maintainer.md GOVERNANCE-maintainer.md
- GOVERNANCE-subprojects.md GOVERNANCE-subprojects.md
- GOVERNANCE.md GOVERNANCE.md
- MAINTAINERS.md MAINTAINERS.md
- REVIEWING.md REVIEWING.md
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

Note: This is the README file for the templates repo. Please use [README-template.md](README-template.md)
as a template for your project README.