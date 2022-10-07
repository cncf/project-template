# Contributor Ladder Template

This is a light contributor ladder template for CNCF projects that requires editing before it is ready to use. Read the markdown comments, `<!-- COMMENT -->`, for additional guidance. The raw markdown uses `TODO` to identify areas that require customization.

Particularly, this file provides you with a menu of options for your project.  Most projects have 3-4 defined contributor roles. We have outlined more roles below than you may need, so select what makes sense for the structure and size of your project. Other roles should be deleted, or combined into an adjacent role.


<!-- template begins here -->

* [Contributor Ladder](#contributor-ladder-template)
    * [Community Participant](#community-participant)
    * [Contributor](#contributor)
    * [Organization Member](#organization-member)
    * [Reviewer](#reviewer)
    * [Maintainer](#maintainer)
* [Inactivity](#inactivity)
* [Involuntary Removal](#involuntary-removal-or-demotion)
* [Stepping Down/Emeritus Process](#stepping-downemeritus-process)
* [Contact](#contact)


## Contributor Ladder

Hello! We are excited that you want to learn more about our project contributor ladder! This contributor ladder outlines the different contributor roles within the project, along with the responsibilities and privileges that come with them. Community members generally start at the first levels of the "ladder" and advance up it as their involvement in the project grows.  Our project members are happy to help you advance along the contributor ladder.

Each of the contributor roles below is organized into lists of three types of things. "Responsibilities" are things that a contributor is expected to do. "Requirements" are qualifications a person needs to meet to be in that role, and "Privileges" are things contributors on that level are entitled to.


### Community Participant
<!--This role spells out what's expected of general community participants.  This is the lowest
level of participation in the project, and as such many projects don't bother to
define it and leave this section out.-->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Community Participant engages with the project and its community, contributing their time, thoughts, etc. Community participants are usually users who have stopped being anonymous and started being active in project discussions.

* Responsibilities:
    * Must follow the [CNCF CoC](https://github.com/cncf/foundation/blob/main/code-of-conduct.md)
* How users can get involved with the community:
    * Participating in community discussions
    * Helping other users
    * Submitting bug reports
    * Commenting on issues
    * Trying out new releases
    * Attending community events
    * [TODO: Other examples of non-contribution participation]


### Contributor
<!-- This role describes people who have just started contributing, or who contribute occasionally but don't participate in project governance or have defined responsibilities.  Usually projects define either this level or Community Participant, but not both.  If you don't define this role, make sure to copy over its requirements to Organization Member -->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Contributor contributes directly to the project and adds value to it. Contributions need not be code. People at the Contributor level may be new contributors, or they may only contribute occasionally.

* Responsibilities include:
    * Follow the CNCF CoC
    * Follow the project contributing guide
* Requirements (one or several of the below):
    * Report and sometimes resolve issues
    * Occasionally submit PRs
    * Contribute to the documentation
    * Show up at meetings, takes notes
    * Answer questions from other community members
    * Submit feedback on issues and PRs
    * Test releases and patches and submit reviews
    * Run or helps run events
    * Promote the project in public
    * Help run the project infrastructure
    * [TODO: other small contributions]
* Privileges:
    * Invitations to contributor events
    * Eligible to become an Organization Member


### Organization Member
<!--This role is used by many projects where you have to be a regular contributor to have the right to vote in project elections, or to be able to operate project
CI/CD automation.  If these rights do not apply to you, then it makes sense to combine this role with the Contributor role.  For most projects, Org Member is the \
lowest level with clearly defined responsibilities and rights, because it is tied to permissions on the project's code repository. -->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: An Organization Member is an established contributor who regularly participates in the project. Organization Members have privileges in both project repositories and elections, and as such are expected to act in the interests of the whole project.

An Organization Member must meet the responsibilities and has the requirements of a Contributor, plus:

* Responsibilities include:
    * Continues to contribute regularly, as demonstrated by having at least [TODO: Number] [TODO: Metric] a year, as demonstrated by [TODO: contributor metrics source]. <!-- Example: "as demonstrated by having at least 50 GitHub contributions per year, as shown by Devstats"-->
* Requirements:
    * Must have successful contributions to the project, including at least one of the following:
        * [TODO: Number] accepted PRs,
        * Reviewed [TODO: Number] PRs,
        * Resolved and closed [TODO: Number] Issues,
        * Become responsible for a key project management area,
        * Or some equivalent combination or contribution
    * Must have been contributing for at least [TODO: Number] months
    * Must be actively contributing to at least one project area
    * Must have two sponsors who are also Organization Members, at least one of whom does not work for the same employer
    * [TODO: other requirements] <!--TODO: such as repository access or enabling 2FA on their GitHub account -->

* Privileges:
    * May be assigned Issues and Reviews
    * May give commands to CI/CD automation
    * Entitled to vote in the [TODO: appropriate election]
    * Can be added to [TODO: Repo Host] teams
    * Can recommend other contributors to become Org Members
    * [TODO: Other Privileges]


The process for a Contributor to become an Organization Member is as follows:

<!-- the process of becoming an organization member is going to depend strongly on how your project manages its infrastructure. TODO: Project leads to fill in exact details of how a contributor becomes an organization member-->
1.
2.
3.

### Reviewer
<!-- Some projects have CI/CD systems that allow for designating people as official reviewers, whose reviews count towards a PR being accepted into the project.  Other projects offer reviewers specific recognition and status.  This role is for either of those kinds of projects. Smaller projects will not use it.-->
<!--TODO: project leads to fill in exact details of this role for your project-->
Description: A Reviewer has responsibility for specific code, documentation, test, or other project areas. They are collectively responsible, with other Reviewers, for reviewing all changes to those areas and indicating whether those changes are ready to merge. They have a track record of contribution and review in the project.

Reviewers are responsible for a "specific area." This can be a specific code directory, driver, chapter of the docs, test job, event, or other clearly-defined project component that is smaller than an entire repository or subproject. Most often it is one or a set of directories in one or more Git repositories. The "specific area" below refers to this area of responsibility.

Reviewers have all the rights and responsibilities of an Organization Member, plus:

* Responsibilities include:
    * Following the reviewing guide
    * Reviewing most Pull Requests against their specific areas of responsibility
    * Reviewing at least [TODO: Number] PRs per year
    * Helping other contributors become reviewers
* Requirements:
    * Experience as a Contributor for at least [TODO: Number] months
    * Is an Organization Member
    * Has reviewed, or helped review, at least [TODO: Number] Pull Requests
    * Has analyzed and resolved test failures in their specific area
    * Has demonstrated an in-depth knowledge of the specific area
    * Commits to being responsible for that specific area
    * Is supportive of new and occasional contributors and helps get useful PRs in shape to commit
* Additional privileges:
    * Has GitHub or CI/CD rights to approve pull requests in specific directories
    * Can recommend and review other contributors to become Reviewers
    
<!-- TODO: define how this works with your specific system.  For example:  "Is listed as Approver in the OWNERS file for certain directories. -->


The process of becoming a Reviewer is:
<!-- TODO: define your exact process here.  What's below is given as an example process for a project that uses Owners files and has defined teams for each project area -->
1. The contributor is nominated by opening a PR against the appropriate repository, which adds their GitHub username to the OWNERS file for one or more directories.
2. At least two members of the team that owns that repository or main directory, who are already Approvers, approve the PR.


### Maintainer
<!-- In the simplest and most common project structures, projects have a single pool of "maintainers" who are collectively responsible for the entire project.  This example defines that role for your project.  If your project has a more complex structure, see the list of specific maintainer roles you might want to define, below. -->
<!--TODO: project leads to fill in exact details of this role for your project-->

Description: Maintainers are very established contributors who are responsible for the entire project. As such, they have the ability to approve PRs against any area of the project, and are expected to participate in making decisions about the strategy and priorities of the project.

A Maintainer must meet the responsibilities and requirements of a Reviewer, plus:

* Responsibilities include:
    * Reviewing at least [TODO: Number] PRs per year, especially PRs that involve multiple parts of the project
    * Mentoring new Reviewers
    * Writing refactoring PRs
    * Participating in CNCF maintainer activities
    * Determining strategy and policy for the project
    * Participating in, and leading, community meetings
* Requirements
    * Experience as a Reviewer for at least [TODO: Number] months
    * Demonstrates a broad knowledge of the project across multiple areas
    * Is able to exercise judgment for the good of the project, independent of their employer, friends, or team
    * Mentors other contributors
    * Can commit to spending at least [TODO: Number] hours per month working on the project
* Additional privileges:
    * Approve PRs to any area of the project
    * Represent the project in public as a Maintainer
    * Communicate with the CNCF on behalf of the project
    * Have a vote in Maintainer decision-making meetings
    

Process of becoming a maintainer:
<!-- TODO: this process will vary widely across projects, both because of project code structure, and because of project governance.  For example, in some projects the Steering Committee approves new Maintainers.  What's below is just an example from a simple project in which the maintainers are also the project leaders, and which uses GitHub OWNERS files. -->
1. Any current Maintainer may nominate a current Reviewer to become a new Maintainer, by opening a PR against the root of the [TODO: main repository name] adding the nominee as an Approver in the OWNERS file.
2. The nominee will add a comment to the PR testifying that they agree to all requirements of becoming a Maintainer.
3. A majority of the current Maintainers must then approve the PR.

<!-- Some projects might add a limit on the percentage of maintainers from a specific organization here.  Obviously this only works if your project has
reached the stage where you have a reasonable diversity of maintainers.  At that point, you can add a statement like this: 
The maintainers will avoid nominating new maintainers from any organization that already employs 50% or more of existing maintainers
-->


<!-- ### ADDITIONAL MAINTAINER ROLES
Some projects have additional, specifically defined maintainer roles because of leadership positions that don't fit within the general maintainer template above, including ones that have special requirements.  In addition to spelling out those requirements, defining and publishing additional maintainer roles can be a way to recruit maintainers in those specific areas, especially non-code maintainers.  Here are examples of special maintainer roles which have been defined by a variety of projects.  As all of these roles are highly dependent on exact project organization, tooling, etc., these roles are not templatable.

* Subproject Maintainer: Owns a distinct subproject or repository of the main project.  Responsible for everything there.  In federation projects, subproject maintainers might be the primary maintainer type.  [Example](https://github.com/kubernetes/community/blob/master/committee-steering/governance/sig-governance.md#subproject-owner)
* Documentation Maintainer: for your Docs leads.  Would include specific documentation targets and experience, and maintaining publication schedules as a requirement.  [Example](https://kubernetes.io/docs/contribute/participate/roles-and-responsibilities/)
* Localizations Maintainers: owns a particular localization, like Japanese or Brazilian Portuguese, across documentation, messages, and websites.  Responsible for making sure those get updated.
* Program Manager: Responsible for timelines and processes within the project, such as bug triage, review timelines, etc.
* Release Manager: owns the release process, either always, cyclically, or per-release.  Responsible for getting releases out on time.  [Example](https://github.com/kubernetes/sig-release/tree/master/release-team/role-handbooks/release-team-lead)
* Patch Maintainer: sometimes different from the release manager, owns the tooling, team, and schedule for patching stable releases. [Example](https://github.com/kubernetes/sig-release/blob/master/release-engineering/role-handbooks/patch-release-team.md)
* Community Manager: owns social media, community metrics, new contributor process, and similar areas.
-->


## Inactivity
<!--TODO: project leads to fill in exact details for how you measure inactivity for your project-->
It is important for contributors to be and stay active to set an example and show commitment to the project. Inactivity is harmful to the project as it may lead to unexpected delays, contributor attrition, and a lost of trust in the project.

* Inactivity is measured by:
    * Periods of no contributions for longer than [TODO: Number] months
    * Periods of no communication for longer than [TODO: Number] months
* Consequences of being inactive include:
    * Involuntary removal or demotion
    * Being asked to move to Emeritus status

## Involuntary Removal or Demotion

Involuntary removal/demotion of a contributor happens when responsibilities and requirements aren't being met. This may include repeated patterns of inactivity, extended period of inactivity, a period of failing to meet the requirements of your role, and/or a violation of the Code of Conduct. This process is important because it protects the community and its deliverables while also opens up opportunities for new contributors to step in.

<!-- TODO: replace with your method of removing/demoting contributors.  If you have a formal governance structure, this would be a good place to assign this to your governance, such as a Steering Committee.
Again, the example below is for a project without formal governance except the maintainers.-->
Involuntary removal or demotion is handled through a vote by a majority of the current Maintainers.

## Stepping Down/Emeritus Process
If and when contributors' commitment levels change, contributors can consider stepping down (moving down the contributor ladder) vs moving to emeritus status (completely stepping away from the project).

Contact the Maintainers about changing to Emeritus status, or reducing your contributor level.

## Contact
* For inquiries, please reach out to:
    *  <!-- TODO: fill in contact info for appropriate group or person for contributor mentorship-->
