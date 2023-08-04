# Design Proposal Template

**Authors**: alice alice@example.com, bob jones bob@example.com

**Begin Design Discussion**: YYYY-MM-DD

**(optional) Status: **implementable, accepted, deferred, rejected, withdrawn, or replaced

**Checklist**:

What goes in this checklist is highly dependent on how your project manages their PRs. The Checklist is intended to serve as a final review for the feature before cutting the release where the feature is available.

- [ ] Prerequisite 1
- [ ] Prerequisite 2
- [ ] Component 1
- [ ] Component 2
- [ ] Docs
- [ ] Tests



## Summary/Abstract

Provide a high-level summary of the proposed change. Keep it short.

This design process establishes a series of standard practices for planning and recording features or changes proposed for the project. The intent is to provide the project a consistent means to track decisions for historical reference and future plans while fully capturing how the feature or change will come to be. Additional benefits include making the process of building the release changelog easier and faster when the feature or change is ready to be released. It is a combination of a feature and effort-tracking document, a product requirements document, and a design document.

## Background

### Motivation and problem space

Describe the need, problem, and motivation for the feature or change and any context required to understand the motivation. 

### Impact and desired outcome

Describe any potential impact this feature or change would have. Readers should be able to understand why the feature or change is important. Briefly describe the desired outcome if the change or feature were implemented as designed. 

### Prior discussion and links

Often these proposals start as an issue, forum post, email and it's helpful to link to those resources in this section to provide context and credit the right people for the idea.

It is vital for projects to be able to track the chain of custody for a proposed enhancement from conception through implementation which can sometimes be difficult to do in a single Github issue, especially when it is a larger design decision or cuts across multiple areas of the project.

The purpose of the design proposal processes is to reduce the amount of "siloed knowledge" in a community. By moving decisions from a smattering of mailing lists, video calls, slack messages, GitHub exchanges, and hallway conversations into a well tracked artifact, the process aims to enhance communication and discoverability.

## (Optional) User/User Story

Define who your the intended users of the feature or change are. Detail the things that your users will be able to do with the feature if it is implemented. Include as much detail as possible so that people can understand the "how" of the system. This can also be combined with the prior sections.

## Goals

List the desired goal or goals that the design is intended to achieve. These goals can be leveraged to structure and scope the design and discussions and may be reused as the "definition of done" -  the criteria you use to know the implementation of the design has succeeded in accomplishing its goals.

## Non-Goals

Describe what is out of scope for the design proposal. Listing non-goals helps to focus discussion and make progress.

## Proposal

This is where we get down to the specifics of what the proposal actually is. It should have enough detail that reviewers can understand exactly what you're proposing, but should not include things like API designs or implementation. This section should expand on the desired outcome and include details on how to measure success.

## Design Details

This section should contain enough information to allow the following to occur:
* potential contributors understand how the feature or change should be implemented
* users or operators understand how the feature of change is expected to function and interact with other components of the project
* users or operators can take action to pre-plan any needed changes within their architecture that impacted by the upcoming feature or change if it's approved for implementation
* decisions or opinions on a specific approach are fully discussed and explained
* users, operators, and contributors can gain a comprehensive understanding of compatibility of the feature or change with past releases of the project.

This may include API specs (though not always required), code snippets, data flow diagrams, sequence diagrams, etc. 

If there's any ambiguity about HOW your proposal will be implemented, this is the place to discuss them. This can also be combined with the proposal section above. It should also address how the solution is backward compatible and how to deal with these incompatibilities, possibly with defaulting or migrations. It may be useful to refer back to the goals and non-goals to assist in articulating the "why" behind your approach.

## Impacts / Key Questions

List crucial impacts and key questions, some of which may still be open. They likely require discussion and are required to understand the trade-offs of the design. During the lifecycle of a design proposal, discussion on design aspects can be moved into this section. After reading through this section, it should be possible to understand any potentially negative or controversial impact of the design. It should also be possible to derive the key design questions: X vs Y.

This will also help people understand the caveats to the proposal, other important details that didn't come across above, and alternatives that could be considered. It can also be a good place to talk about core concepts and how they relate. It can be helpful to explicitly list the pros and cons of each decision. Later, this information can be reused to update project documentation, guides, and Frequently Asked Questions (FAQs).

### Pros
Pros are defined as the benefits and positive aspects of the design as described. It should further reinforce how and why the design meets its goals and intended outcomes. This is a good place to check for any assumptions that have been made in the design.
### Cons
Cons are defined as the negative aspects or disadvantages of the design as described. This section has the potential to capture outstanding challenge areas or future improvements needed for the project and could be referenced in future PRs and issues. This is also a good place to check for any assumptions that have been made in the design.
## Risks and Mitigations

Describe the risks of this proposal and how they can be mitigated. This should be broadly scoped and describe how it will impact the larger ecosystem and potentially adopters of the project; such as if adopters need to immediately update, or support a new port or protocol. It should include drawbacks to the proposed solution. 

### Security Considerations

When attempting to identify security implications of the changes, consider the following questions:
* Does the change alter the permissions or access of users, services, components - this could be an improvement or downgrade or even just a different way of doing it?
* Does the change alter the flow of information, events, and logs stored, processed, or transmitted?
* Does the change increase the 'surface area' exposed - meaning, if an operator of the project or user were to go rogue or be uninformed in its operation, do they have more areas that could be manipulated unfavorably?
* What existing security features, controls, or boundaries would be affected by this change?

This section can also be combined into the one above.


## (Optional) Future Milestones

List things that the design will enable but that are out of scope for now. This can help understand the greater impact of a proposal without requiring to extend the scope of a proposal unnecessarily.

## (Optional) Implementation Details

Some projects may desire to track the implementation details in the design proposal. Some sections may include:

### Testing Plan

An overview on the approaches used to test the implementation.

### Update/Rollback Compatibility

How the design impacts update compatibility and how users can test rollout and rollback.

### Scalability

Describe how the design scales, especially how changes API calls, resource usage, or impacts SLI/SLOs.

### Implementation Phases/History

Describe the development and implementation phases planned to break up the work and/or record them here as they occur. Provide enough detail so readers may track the major milestones in the lifecycle of the design proposal and correlate them with issues, PRs, and releases occurring within the project.
