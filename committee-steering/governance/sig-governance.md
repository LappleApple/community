# SIG Roles and Organizational Governance

This charter adheres to the conventions described in the [Kubernetes Charter README].
It will be updated as needed to meet the current needs of the Kubernetes project.

In order to standardize Special Interest Group efforts, create maximum
transparency, and route contributors to the appropriate SIG, SIGs should follow
these guidelines:

- Create a charter and have it approved according to the [SIG charter process]
- Meet regularly, at least for 30 minutes every 3 weeks, except November and
December
- Keep up-to-date meeting notes, linked from the SIG's page in the community
repo
- Record meetings and make them publicly available on the
[Kubernetes Community YouTube playlist]  
- Report activity with the community via the kubernetes-dev@ mailing list at
least once a year. 
  - Each SIG is assigned an update during the [monthly community meeting]
  throughout the year from sig-contributor-experience. The meeting host will publish the notes to the
  kubernetes-dev mailing list with the update.  
  - This is separate from the [annual report]. 
- Participate in release planning meetings and retrospectives, and burndown
meetings, as needed
- Ensure related work happens in a project-owned github org and repository, with
 code and tests explicitly owned and supported by the SIG, including issue
 triage, PR reviews, test-failure response, bug fixes, etc.
- Use the [forums provided] as the primary means of working, communicating, and
collaborating, as opposed to private emails and meetings  
- Ensure contributing instructions (CONTRIBUTING.md) are defined in the SIGs
folder located in the Kubernetes/community repo if the groups contributor steps
and experience are different or more in-depth than the documentation listed in
the general [contributor guide] and [devel] folder.  
- Help and sponsor working groups that the SIG is interested in investing in  
- Track and identify all SIG features in the current release and [k/enhancements]

The process for setting up a SIG or Working Group (WG) is listed in the
[sig-wg-lifecycle] document.

## Roles

<img src="Roles%20diagram.png" height="50%" width="50%">

### Notes on Roles

Within this section "Lead" refers to someone who is a member of the union
 of a Chair, Tech Lead or Subproject Owner role. There is no one lead to any
 Kubernetes community group. Leads have specific decision-making power over some
 part of a group and thus additional accountability. Each role is detailed below.  

- Initial roles are defined at the founding of the SIG or Subproject as part
of the acceptance of that SIG or Subproject.

#### Activity Expectations  

- Leads *MUST* remain active and responsive in their roles, aside from times when personal/extenuating circumstances prevent it.
- Leads taking an extended leave of one or more months *MUST* coordinate with other leads to ensure the role is adequately staffed during the leave.
- Leads going on leave for 1-3 months *SHOULD* work with other Leads to identify a temporary replacement.
- Leads *SHOULD* remove any other leads or roles that have not communicated a leave of absence and either cannot be reached for more than one month or are not fulfilling their documented responsibilities for more than one month.
  - This may be done through a [super-majority] vote of Leads. If there are not enough *active* Leads, then a [super-majority] vote between Chairs, Tech Leads and Subproject Owners may decide the removal of the Lead.

#### Requirements

- Leads *MUST* be at least a ["member" on our contributor ladder] to
be eligible to hold a leadership role within a SIG.
- SIGs *MAY* prefer various levels of domain knowledge depending on the
role. This should be documented.  
- Leads *MUST* support onboarding new contributors to grow the
community and mitigate risk.

#### Escalations

- Lead membership disagreements *SHOULD* be escalated to the SIG Chairs. SIG Chair
membership disagreements may be escalated to the Steering Committee.

#### On-boarding and Off-boarding Leads

- Leads *MAY* decide to step down at anytime and propose a replacement.  Use
lazy consensus amongst other Leads with fallback on majority vote to accept
the proposal. The new Lead candidate *SHOULD* be supported by a majority of 
SIG contributors or the Subproject contributors (as applicable).
- Leads *MAY* select additional leads through a [super-majority] vote
amongst leads. This *SHOULD* be supported by a majority of SIG contributors or
Subproject contributors (as applicable).

### Chair

- Number: 2-3
- Membership tracked in [sigs.yaml]  
  - If no tech lead or program manager role are present, Chair assumes responsibilities from [#tech-lead] and [#program-manager] sections.
  
The SIG Chair is responsible for driving the *WHY*: the vision and development 
priorities—and making sure the SIG fulfills its operations- and process-related
obligations.

Developing the *WHY* remains a group effort in collaboration with other Leads and SIG 
contributors, but SIG Chairs take the lead in optimizing value and guiding the group 
toward outcomes. 

**Delivery Vision and Strategy**: 
- *MUST* lead their SIG to decide upon the top-priority KEPs to be delivered 
during an upcoming release cycle; *SHOULD* work out a lightweight process 
with other SIG leads
- *MUST* ensure that, when a KEP involves multiple SIGs, alignment and 
coordination with those other SIGs is occurring. *MAY* delegate this to other 
leads. 
- *MUST* ensure their KEPs for the upcoming cycle are communicated to the 
Release Team in a timely way; *MAY* delegate oversight to other SIG leads
- *MUST* ensure that the SIG’s enhancements for the current release are tracked; 
*MAY* delegate this to other Leads
- *SHOULD* communicate the reasoning behind their prioritization decisions 
regarding KEPs and other increments of work
- *SHOULD* serve as point of contact for the release team regarding enhancements the 
current release, but *MAY* delegate to another Lead to fulfill these responsibilities
- *SHOULD* lead their SIG in creating a roadmap or strategy document, and *MAY* 
delegate this to other Leads
- *SHOULD* publish the roadmap or strategy document for users and contributors 
to discover
- *SHOULD* ensure their SIG’s roadmap is discussed at regular meetings and invite
 feedback from contributors
- *SHOULD* drive backlog refinement activities to ensure the highest-value work is
 prioritized; *SHOULD* coordinate this with other Leads
- *SHOULD* define how priorities and commitments are managed and delegate to other 
leads as needed
- *SHOULD* talk to users/customers to collect insights for the SIG to act on through
 KEPs and other development

**Operations and Processes**:
- *MUST* present yearly [annual report] for the group but *SHOULD* get help with 
curation from other SIG participants
- *MUST* ensure that their SIG has a clear path/ladder for contributors to rise to 
reviewer and approver, but *MAY* delegate the process to other leads and engaged 
contributors
- *MUST* report activity with the community via k-dev mailing list at least once 
a quarter (slides, video from kubecon, etc)
- *MUST* organize KubeCon/CloudNativeCon Intros and Deep Dives with CNCF Event staff 
and approve presented content but *MAY* delegate to other contributors to create 
material and present  
- *MUST* coordinate sponsored working group updates to the SIG and the wider Community; 
*MAY* delegate this role to other Leads
- *MUST* coordinate communication and be a connector with other community groups like 
SIGs and the Steering Committee but *MAY* delegate the actual communication and creation 
of content to other contributors where appropriate  
- *MUST* ensure there is a maintained CONTRIBUTING.md document in the appropriate SIG 
folder if the contributor experience or on-boarding knowledge is different than in the 
general [contributor guide]. *MAY* delegate to contributors to create or update.
- *MUST* ensure meetings are recorded and made available. *MAY* delegate to contributors 
to create or update.
- *MUST* organize a main group meeting and make sure [sigs.yaml] is up to date, including 
subprojects and their meeting information. *MAY* delegate to contributors to create or update.
- *SHOULD* delegate the need for subproject meetings to subproject owners  
- *SHOULD* facilitate meetings but *MAY* delegate to other Leads or future chairs/chairs-in-training
- *SHOULD* drive charter changes (including creation) to get community buy-in but *MAY* delegate 
content creation to SIG contributors.


### Tech Lead

  - Number: 1-3
  - Membership tracked in [sigs.yaml]
  - Role description in [technical-lead.md]

The SIG Technical Lead is responsible for driving the *HOW*: the technical implementation 
that supports development. This is an *optional* role.

Developing the *HOW* remains a group effort in collaboration with SIG Chair Leads and 
SIG contributors, but this role takes the lead in driving collaboration and discussion 
about implementation.

- *MUST* lead the SIG in creating a clear and consistent technical vision, and *SHOULD* 
publish artefacts describing this vision for the benefit of users, contributors, and 
other SIGs 
- *MUST* ensure that other members of the SIG—especially leads, approvers, and reviewers—
can access information/artefacts about the technical vision, and communicate how best 
to challenge and raise questions about it
- *MUST* track the technical quality of SIG deliverables if a roadmap exists
- *MUST* provide senior leadership to the SIG’s short-term and long-term technical vision
- *MUST* maintain a  wide-range understanding of the SIGs work in correlation to the 
whole community. Establishing future plans by continuously working on the technical 
vision of the SIG.
- *MUST* ensure that the team utilizes appropriate engineering practices which apply 
to the whole Kubernetes organization, such as using Prow for Continuous Integration 
(CI) practices
- *MUST* continuously evaluate technical challenges within the SIG and work towards 
removing them as part of the vision
- *MUST* take changing environments into account to adapt the technical vision if needed
- *MUST* align with the SIG Chairs and other leads on deciding the top-priority KEPs to 
be delivered during an upcoming release cycle; *SHOULD* inform and influence those 
decisions as much as possible
- *MUST* support SIG Chair in driving alignment and coordination among interdependent 
SIGs; *SHOULD* lead these alignment and coordination efforts as time allows
- *MUST* be involved in the SIG’s source code base to raise needs and take decisions
- *MUST* actively identify risk and maintain a high level of trust with other members 
of the SIG
- *MUST* mentor team members around solving technical tasks; *SHOULD* look for delegation
 opportunities
- *SHOULD* support the SIG Chair as a secondary point of contact for the release team 
regarding enhancements the current release
- *SHOULD* support SIG Chair in identifying, tracking, and maintaining the SIG’s 
enhancements for the current release
- *SHOULD* guide subprojects to resolve technical issues and decisions
- *SHOULD* watch out for “good first issues” and “help wanted” items to delegate work to 
contributors; *MAY* delegate this to other leads or contributors
- *SHOULD* oversee decommission of subprojects that are no longer wanted, or delegate 
to contributors
- *MAY* Establish new subprojects
- *MAY* talk to users/customers to collect insights for the SIG to act on through KEPs
 and other development

### Program Manager

  - Number: 1-2
  - Membership tracked in [sigs.yaml]
  - Role description in [program-manager.md]
  
The Program Manager is responsible for driving delivery effectiveness—i.e. making sure 
things get done efficiently, software is shipped, workflows are continuously improved. 

Like the technical lead, this is an *optional* role. 

- *MUST* receive the same permissions as other SIG leads
- *MUST* listen and observe the SIG to devise process improvements based on expressed needs
- *MUST* prioritize processes that are asynchronous and lightweight—ideally increasing 
transparency and reducing administrative overhead or confusion
- *MUST* propose solutions based on the specific needs of the group, and not impose theory 
or frameworks prescriptively or in a vacuum
- *MUST* collaborate with other SIG leadership as early and often as possible when ideating/
developing new processes or suggesting improvements, to achieve buy-in and build trust
- *MUST* guide the SIG to break down complexity into smaller increments of value
- *MUST* drive process development and improvements related to SIG communications, delegation,
 collaboration, and alignment with other SIGs
- *MUST* continuously surface process gaps and weaknesses that introduce risk, create waste,
 duplicate efforts, or exclude contributors, and raise these issues to other SIG Leads for
 discussion and remediation
- *MUST* advocate for processes aimed at driving delivery effectiveness, such as issue 
triage, roadmapping/North Star vision creation, backlog refinement, and KEP planning; 
*SHOULD* delegate setup and execution to other SIG leads and contributors
- *MUST* coach/mentor other SIG leads and contributors to facilitate processes, meetings, 
and activities that drive achievement of delivery outcomes, to reduce bottlenecks and risk
- *MUST* guide the SIG to follow established practices in Kubernetes, from adherence to 
release deadlines to enforcing the Code of Conduct; *SHOULD* delegate follow-up to other 
Leads and contributors
- *MUST* advise the SIG on tooling that supports delivery effectiveness and smooth workflows,
 such as GitHub project boards and creative use of GitHub Issues to track work; *SHOULD*
 delegate setup to contributors
- *MUST* drive compromise to mitigate conflict and guide the group to focus on outcomes
- *MUST* encourage the SIG to prioritise contributor experience in order to drive delegation
 of work and reduce risk; *SHOULD* encourage related activities such as creating “career 
ladders” and designing work packages that engaged contributors can drive via small teams
- *SHOULD* propose improvements to cross-SIG coordination and communication
- *SHOULD* advise the SIG Chair and Technical Leads on prioritization, roadmapping, and 
strategic development, adopting a neutral and “if asked” ap 
- *SHOULD* support the SIG Chair in delegating operational tasks to contributors and other
 leads safely and responsibly
- *SHOULD* advise the SIG Chair in organizing the process related to prioritizing, deciding
 upon, and communicating the top-priority KEPs for the release cycle
- *SHOULD* advise the SIG Technical Leads (if relevant) in driving processes and communications
 related to developing and communicating the technical vision
- *SHOULD* be involved in the day-to-day workings of the SIG—attending (or in some cases 
hosting) meetings, following discussions on Slack, learning about the priorities and technical
 responsibilities and plans for the group
- *SHOULD* drive periodic evaluation of established processes to ensure they’re working, by
 asking the group for feedback and measuring impact with metrics
- *SHOULD* guiding their SIG to adopt prioritisation frameworks that support delivery of 
the highest-value, highest-impact work 
- *SHOULD* design lightweight communication mechanisms that reinforce timely responsiveness
 to deadlines and external requests, such as monthly drumbeats

### Subproject Owner

- Subproject Owners
  - Scoped to a subproject defined in [sigs.yaml]
  - Seed leads and contributors established at subproject founding
  - *SHOULD* be an escalation point for technical discussions and decisions in
  the subproject
  - *SHOULD* set milestone priorities or delegate this responsibility
  - Number: 2-3
  - Membership tracked in [sigs.yaml]

### All Leads

- *SHOULD* maintain health of at least one subproject or the health of the SIG
- *SHOULD* show sustained contributions to at least one subproject or to the
  SIG
- *SHOULD* hold some documented role or responsibility in the SIG and / or at
  least one subproject
    (e.g. reviewer, approver, etc)
- *MAY* build new functionality for subprojects
- *MAY* participate in decision making for the subprojects they hold roles in
- Includes all reviewers and approvers in [OWNERS] files for subprojects
- *MUST* take an [inclusive speaker training course] in support of our community values
within 30 days from the date of their appointment.

### Security Contact

- Security Contact
  - *MUST* be a contact point for the Product Security Committee to reach out to
   for triaging and handling of incoming issues
  - *MUST* accept the [Embargo Policy]
  - Defined in `SECURITY_CONTACTS` files, this is only relevant to the root file
   in the repository. Template [SECURITY_CONTACTS]

#### Subproject Creation

---

Option 1: by SIG Technical Leads

- Subprojects may be created by [KEP] proposal and accepted by [lazy-consensus] with fallback on majority vote of
  SIG Technical Leads.  The result *SHOULD* be supported by the majority of SIG Leads.
  - KEP *MUST* establish subproject owners
  - [sigs.yaml] *MUST* be updated to include subproject information and [OWNERS] files with subproject owners
  - Where subprojects processes differ from the SIG governance, they must document how
    - e.g. if subprojects release separately - they must document how release and planning is performed

Option 2: by Federation of Subprojects

- Subprojects may be created by [KEP] proposal and accepted by [lazy-consensus] with fallback on majority vote of
  subproject owners in the SIG.  The result *SHOULD* be supported by the majority of leads.
  - KEP *MUST* establish subproject owners
  - [sigs.yaml] *MUST* be updated to include subproject information and [OWNERS] files with subproject owners
  - Where subprojects processes differ from the SIG governance, they must document how
    - e.g. if subprojects release separately - they must document how release and planning is performed

Subprojects may create repos under *github.com/kubernetes-sigs* through [lazy-consensus] of subproject owners.

---

- Subprojects must define how releases are performed and milestones are set.  Example:

> - Release milestones
>   - Follows the kubernetes/kubernetes release milestones and schedule
>   - Priorities for upcoming release are discussed during the SIG meeting following the preceding release and shared through a PR. Priorities are finalized before feature freeze.
> - Code and artifacts are published as part of the kubernetes/kubernetes release

### Technical processes

Subprojects of the SIG *MUST* use the following processes unless explicitly following alternatives
they have defined.

- Proposing and making decisions
  - Proposals sent as [KEP] PRs and published to googlegroup as announcement
  - Follow [KEP] decision making process

- Test health
  - Canonical health of code published to [dashboard]
  - Consistently broken tests automatically send an alert to their google group.
  - SIG contributors are responsible for responding to broken tests alert. PRs that break tests should be rolled back if not fixed within 24 hours (business hours).
  - Test dashboard checked and reviewed at start of each SIG meeting.  Owners assigned for any broken tests and followed up during the next SIG meeting.

Issues impacting multiple subprojects in the SIG should be resolved by either:

- Option 1: SIG Technical Leads
- Option 2: Federation of Subproject Owners

### SIG Retirement

- In the event that the SIG is unable to regularly establish consistent quorum
  or otherwise fulfill its Organizational Management responsibilities
  - after 3 or more months it *SHOULD* be retired
  - after 6 or more months it *MUST* be retired

[k/enhancements]: https://github.com/kubernetes/enhancements
[forums provided]: /communication/README.md
[lazy-consensus]: http://en.osswiki.info/concepts/lazy_consensus
[super-majority]: https://en.wikipedia.org/wiki/Supermajority#Two-thirds_vote
[KEP]: https://git.k8s.io/enhancements/keps/NNNN-kep-template/README.md
[sigs.yaml]: https://github.com/kubernetes/community/blob/master/sigs.yaml
[OWNERS]: contributors/devel/owners.md
[SIG Charter process]: https://git.k8s.io/community/committee-steering/governance/README.md
[Kubernetes Charter README]: https://git.k8s.io/community/committee-steering/governance/README.md
[Embargo Policy]: https://git.k8s.io/security/private-distributors-list.md#embargo-policy
[SECURITY_CONTACTS]: https://github.com/kubernetes/kubernetes-template-project/blob/master/SECURITY_CONTACTS
[sig-wg-lifecycle]: /sig-wg-lifecycle.md
["member" on our contributor ladder]: /community-membership.md
[Kubernetes Community YouTube playlist]: https://www.youtube.com/channel/UCZ2bu0qutTOM0tHYa_jkIwg
[annual report]: ./annual-reports.md
[contributor guide]: /contributors/guide/README.md
[devel]: /contributors/devel/README.md
[#tech-lead]: #Tech-Lead
[Google group]: https://groups.google.com/forum/#!forum/kubernetes-sig-config
[dashboard]: https://testgrid.k8s.io/
[monthly community meeting]: /events/community-meeting.md
[inclusive speaker training course]: https://training.linuxfoundation.org/training/inclusive-speaker-orientation/
[technical-lead.md]: /contributors/chairs-and-techleads/technical-lead.md
[program-manager.md]: /contributors/chairs-and-techleads/program-manager.md
