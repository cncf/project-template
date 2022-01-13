# [TODO:PROJECTNAME] Project Governance

This is an example governance document for projects that consist of a group
of smaller, semi-independent projects.  See [GOVERNANCE.md](/GOVERNANCE.md)
for more information.  Thanks to the Konveyor Project for portions of the text
below.

This is a template document for CNCF projects that requires editing
before it is ready to use. Read the markdown comments, `<!-- COMMENT -->`, for
additional guidance. The raw markdown uses `TODO` to identify areas that
require customization.  Replace [TODO: PROJECTNAME] with the name of your project.

This Template assumes that you are using the Contributor Ladder template as well.

<!-- template begins here-->

The [TODO:PROJECTNAME] umbrella project is composed as a federation of individual projects,
some independent and some interdependent, each of which focuses on some aspect
of [TODO:Goals of umbrella project].  Our governance reflects this federated structure.

- [Values](#values)
- [Individual Project Governance](#individual-project-governance)
- [Steering Committee](#steering-committee)
  - [Steering Committee Duties](#steering-committee-duties)
  - [Steering Committee Elections](#steering-committee-elections)
- [Code of Conduct Committee](#code-of-conduct-committee)
- [Adding New Subprojects](#adding-new-subprojects)
- [Removing Projects](#removing-projects)

## Values

<!-- This is where you put the core values or principles of your project, like
openness, distributed design, fairness, diversity, etc.

References and Examples
* https://www.apache.org/theapacheway/
* https://kubernetes.io/community/values/

See https://contribute.cncf.io/maintainers/governance/charter for guidance and
additional examples.  The values below are just example values as a jumping-off
point for your project's actual values.  -->

The [TODO: PROJECTNAME] and its leadership embrace the following values:

* Openness: Communication and decision-making happens in the open and is discoverable for future
  reference. As much as possible, all discussions and work take place in public
  forums and open repositories.

* Fairness: All stakeholders have the opportunity to provide feedback and submit
  contributions, which will be considered on their merits.

* Community over Product or Company: Sustaining and growing our community takes
  priority over shipping code or sponsors' organizational goals.  Each
  contributor participates in the project as an individual.

* Inclusivity: We innovate through different perspectives and skill sets, which
  can only be accomplished in a welcoming and respectful environment.

* Participation: Responsibilities within the project are earned through
  participation, and there is a clear path up the contributor ladder into leadership
  positions.

## Individual Project Governance

<!-- the below assumes that you want to mandate a simple, maintainer-driven
governance structure for each subproject, which we recommend.-->

All active Maintainers of each subproject, as defined in the Contributor Ladder, are
members of that project's Maintainer Committee, which governs that project.  The
subproject's Maintainer Committee is responsible for the following project governance
activities:

* Ensuring that the subproject creates and publishes regular releases;
* Holding regular, subproject-wide discussions on issues and planning;
* Monthly review of project contributors for advancement on the Contributor Ladder;
* Making final decisions on subproject changes that involve controversial trade-offs;
* Responding to security compromise reports;
* Supporting the Code of Conduct within their subproject and referring violations
  to the Code of Conduct Committee.

Additionally, the project's Maintainer Committee will select, by majority vote, one
representative to the Steering Committee.  This representative need not
be a member of the subproject's Maintainer Committee, and will be replaced or
renewed by the committee annually.

Should a member of the Maintainer Committee cease being active in the subproject,
violate the Code Of Conduct, or need to be removed for some other reason, they
may be removed by a 2/3 majority vote of the other Committee members, or a
majority vote of the Steering Committee.

## Steering Committee

The overall [TODO:PROJECTNAME] umbrella project is governed by a Steering
Committee, which is selected as follows:

* One Maintainer representative from each member subproject
* [TODO:Number] general "Community Representatives"

<!-- depending on your project, you may want to have other kinds of representatives,
such as an End User rep or a CNCF SIG rep.  Add those above.  Examples:
* [TODO:Number] general "Maintainer Representatives"
* -->

### Steering Committee Duties

The Steering Committee is responsible for the following tasks, any of which may
be delegated to a person or group selected by the committee:

* Reviewing and deciding on new projects to add to [TODO:PROJECTNAME]
* Arbitrating inter-project disagreements
* Selecting the Code of Conduct Committee and ratifying CoC judgements
* Removing projects which have become inactive
* Acting on escalated security or code quality issues
* Resolving issues that individual projects are unable to resolve
* Administering project infrastructure, intellectual property, and resources
* Determining overall direction for advocacy and marketing
* Issuing statements on behalf of [TODO:PROJECTNAME] and its subprojects
* Reviewing and approving Contributor Ladder advancement for participants who
  work on the overall umbrella project

In performance of these duties, the Steering Committee will hold a monthly meeting
that is open to all contributors.  The Committee may hold additional, closed meetings
in order to discuss non-public issues such as security exploits, CoC enforcement,
and legal questions.

Steering Committee members are expected to advocate for all of [TODO:PROJECTNAME], not just
certain projects or corporate sponsors, comply with and support the Code of
Conduct, and be professional and compassionate in all of their dealings with
project participants.

### Steering Committee Elections

The Community Representative(s) will be elected by the collective Members
of all subprojects, as defined in the Contributor Ladder.  They
will be elected annually.

<!-- if having other kinds of representatives, define how they are elected here -->

Once per year, the Steering Committee will select between two and three Election
Officers to run the annual election and sets the dates for the election.  Election
Officers should be project Members in good standing, not running for election
themselves, and represent more than one project employer.

These officers will update the list of eligible  Members according to
project records, send out announcements, and conduct the election.  The election
starts with a call for nominations, which lasts for at least one week, and will
include a period for project Members to request changes to their voting status.
Candidates may nominate themselves, or they may be nominated by their colleagues.

The election itself will last for at least one week, and is conducted as a
preference election online, using a method such as Condorcet or IRV.  The
Election Officers will announce the selected candidates at the next regular
community meeting.

## Code of Conduct Committee

<!--omit the below if you've already defined a detailed CoC Committee elsewhere,
or are relying entirely on the CNCF for CoC enforcement-->

In order to review and enforce the Code of Conduct, the Steering Committee selects
[TODO:Number, suggest "3 to 5"] people to be on the Code of Conduct Committee.  
These individuals will be chosen based on their community management and code of conduct
experience, with diverse representation across the committee, including employer, gender,
race, background, and region of the world.  To avoid fatigue, the Steering Committee will
replace at least [TODO:Number] member of the CoC Committee each year.  Members of the
committee do not need to be members of [TODO:PROJECTNAME] if they have sufficient other
expertise.

The CoC Committee will receive reports of conduct violations confidentially,
and will discuss them in closed meetings.  If a report is determined to be a
violation, they will recommend action on it appropriate to the scale, nature,
and context of the violation, from requiring an apology, up to expulsion of an
individual from the project.  In the event that a contributor is to be demoted
or expelled, the CoC Committee will forward this recommendation to the Steering
Committee who will ratify it in a closed meeting.  Should a member of the
Steering Committee be the offender or the reporter, this recommendation will
instead be forwarded to the CNCF staff for final arbitration.

## Adding New Subprojects

During the monthly Steering meeting, any project member may recommend projects
to become part of [TODO:PROJECTNAME].  These projects should have the following
characteristics:

* Have a mission of [TODO:Goals of umbrella project];
* Are appropriately licensed and governed or willing to become so;
* Are under active development;
* Consist of high quality code and designs.

Before submitting an application to the Steering Committee, the applying project
must hold an internal consensus vote of all major contributors to join
[TODO:PROJECTNAME].  The Steering Committee will then review the
application, and decide whether or not to accept it.  If it is accepted, the Committee
will assign one person to assist the subproject in their integration.

In some cases, promising but incomplete projects may be accepted as Experimental
Subprojects.  Such Experimental Subprojects will be considered part of
[TODO:PROJECTNAME], but will be marked as Experimental on the website and in code
repositories, in order to inform users.  Experimental Subproject Members are considered
Members of [TODO:PROJECTNAME], but the subproject is not entitled to a representative on the
Steering Committee.  Steering will review Experimental Subprojects at least twice
per year to determine if they have matured to full subproject status.

## Removing Projects

In some cases, projects will become inactive or unmaintainable, or wish to separate
from [TODO:PROJECTNAME]. Any Steering Committee member may propose removal of a project on
these grounds, and Steering can confirm this with a majority vote.

Projects which still have contributors will then be moved to a repository in their
own namespace. Projects which have ceased all activity are moved to a
[TODO:Name of archive namespace] namespace.
