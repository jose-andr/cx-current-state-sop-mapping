# Future Operating Model Signals

## Purpose

This file captures future operating model signals emerging from current-state SOP mapping across:

- Customer Data and Systems Support
- Customer Focus Information Support

The purpose is to preserve evidence for later design and business case development without prematurely defining the future structure.

This file should help translate current-state observations into possible future capability, governance, workflow, system and architecture implications.

## Current status

Status: Draft discovery placeholder.

Signals should be validated after current-state SOP walkthroughs, pain point review and cross-function synthesis.

## Important boundary

This file identifies signals only.

It does not define a confirmed future operating model.

It should not assume:

- a new team structure
- a new platform
- a new reporting function
- full automation
- merged responsibilities
- broad CX measurement and analysis

Future model design should happen only after current-state evidence is validated.

## Signal inventory

| Signal ID | Current-state signal | Seen in | Possible future operating model implication | Status |
|---|---|---|---|---|
| FOM-001 | Customer data quality and service knowledge quality both affect staff confidence. | Both functions | Future CX model may need connected governance for trusted customer data and trusted service knowledge. | To validate |
| FOM-002 | Current work is often corrective rather than preventative. | Both functions | Future model may need prevention controls, quality monitoring and root cause feedback loops. | To validate |
| FOM-003 | Ownership and decision rights may be unclear. | Both functions | Future model may need named owners, stewards, approvers and escalation authorities. | To validate |
| FOM-004 | Work depends on manual review and officer judgement. | Both functions | Future model should define which decisions remain human-led and which checks can be supported by automation. | To validate |
| FOM-005 | Informal channels support workflow. | Both functions | Future model may need visible request states, approval states, review dates and completion tracking. | To validate |
| FOM-006 | System and support boundaries may be unclear. | Both functions | Future support model may need categories for data, knowledge, CRM user guidance, access, defect and technical support. | To validate |
| FOM-007 | Service information may be duplicated across tools. | Customer Focus Information Support | Future architecture may need source-of-truth rules and reusable knowledge objects. | To validate |
| FOM-008 | Customer records may require cleansing, deduplication and ongoing quality checks. | Customer Data and Systems Support | Future architecture may need customer data quality controls, MDM principles and duplicate prevention. | To validate |
| FOM-009 | Urgent information requires rapid coordination. | Customer Focus Information Support | Future model may need urgent update workflows, temporary content lifecycle rules and staff alert mechanisms. | To validate |
| FOM-010 | Recurring issues reveal improvement opportunities. | Both functions | Future model may need a feedback loop from operational support into service, system, data and knowledge improvement. | To validate |
| FOM-011 | Future omnichannel depends on foundational quality. | Both functions | Future model should treat data quality and service knowledge as prerequisites for channel consistency. | To validate |
| FOM-012 | Work continuity may depend on individual knowledge. | Both functions | Future model may need documented SOPs, backup coverage and shared repositories. | To validate |

## Future capability areas

## 1. Customer data quality capability

Potential future model elements:

- customer data quality standards
- duplicate detection and resolution rules
- data correction authority
- data cleansing workflows
- exception queues
- data ownership model
- prevention controls for duplicate creation
- feedback loops into user guidance or system improvement

Evidence to gather:

- duplicate volume and types
- correction effort
- repeated causes of data quality issues
- unresolved ownership questions
- system constraints
- manual workarounds

## 2. Service knowledge capability

Potential future model elements:

- service information ownership
- content standards for first contact resolution
- Service Directory governance
- editor support model
- approval pathways
- review and expiry cycles
- urgent update workflows
- source-of-truth rules
- reusable knowledge objects

Evidence to gather:

- duplicated content
- outdated or unclear entries
- editor support requests
- urgent updates and hot topics
- message on hold lifecycle issues
- content gaps that cause escalations

## 3. Request triage and routing capability

Potential future model elements:

- shared issue taxonomy
- structured request intake
- clear routing rules
- escalation thresholds
- ownership of unresolved issues
- distinction between data, knowledge, access, system and technical issues
- issue status visibility

Evidence to gather:

- misrouted requests
- unclear CRM support requests
- handoff delays
- requests requiring multiple owners
- repeated support categories
- manual triage effort

## 4. Workflow and lifecycle management capability

Potential future model elements:

- work queues
- status states
- approval states
- review dates
- expiry dates
- retirement states
- completion confirmation
- audit trail
- backup and handover mechanisms

Evidence to gather:

- manual trackers
- email-based approvals
- Teams-based decisions
- untracked follow-up
- outdated temporary information
- work dependent on memory

## 5. Continuous improvement capability

Potential future model elements:

- root cause review of repeat issues
- pattern capture
- feedback from staff questions
- upstream prevention recommendations
- knowledge improvement backlog
- system improvement backlog
- data quality prevention backlog

Evidence to gather:

- repeat duplicate creation causes
- repeat CRM questions
- repeat content gaps
- repeat urgent update issues
- staff workarounds
- issues that return after correction

## 6. Omnichannel readiness capability

Potential future model elements:

- trusted customer identity
- trusted service knowledge
- reusable service content
- channel-neutral information objects
- cross-channel consistency checks
- source-of-truth rules
- human review thresholds
- quality controls before automation

Evidence to gather:

- content suitable for reuse
- content not safe for reuse
- information duplicated across channels
- customer data issues affecting channel continuity
- staff guidance that could become reusable knowledge
- gaps that would block chatbot, web, CRM or self-service reuse

## Operating model design principles

Use these principles during later synthesis.

## Principle 1: Keep actual work visible

Do not design around aspirational work that was not performed in practice.

Future roles and capabilities should be grounded in validated current-state evidence.

## Principle 2: Separate data quality from service knowledge, but connect governance

Customer data and service knowledge are different domains.

They should not be collapsed into one vague support function.

However, they both need clear ownership, quality controls and feedback loops.

## Principle 3: Automate support, not accountability

Automation may support detection, reminders, routing, status visibility and consistency checks.

Accountability for sensitive data, customer-facing information and disputed decisions must remain clear.

## Principle 4: Treat informal workarounds as evidence

Email, Teams, spreadsheets and personal relationships may reveal missing workflow, governance or system support.

Do not dismiss workarounds as noise.

Map what they are compensating for.

## Principle 5: Design for lifecycle, not one-off updates

Customer data and service knowledge both degrade over time.

Future model should include creation, review, correction, escalation, retirement and prevention.

## Principle 6: Build omnichannel on trusted foundations

More channels will not improve service if the underlying customer data and service knowledge are inconsistent.

Future omnichannel capability depends on trusted, governed, reusable information.

## Future operating model hypothesis template

Use this template to record hypotheses after validation.

## Hypothesis: [hypothesis name]

| Attribute | Details |
|---|---|
| Hypothesis ID |  |
| Description |  |
| Current-state evidence |  |
| Related function | Customer Data and Systems Support / Customer Focus Information Support / Both |
| Related SOPs |  |
| Capability area |  |
| Problem addressed |  |
| Future-state implication |  |
| Risk if ignored |  |
| Business case value |  |
| Validation needed |  |
| Status | Proposed / validated / rejected / deferred |

## Business case evidence categories

| Evidence category | Example evidence to collect | Why it matters |
|---|---|---|
| Volume | Number of duplicate records, content updates, urgent updates or support requests. | Shows scale of work. |
| Effort | Time spent cleansing, checking, chasing approval or manually updating tools. | Shows capacity impact. |
| Risk | Outdated guidance, incorrect records, inconsistent advice or unresolved ownership. | Shows service and governance risk. |
| Rework | Repeat corrections, repeated questions or repeated content fixes. | Shows avoidable effort. |
| Delay | Time waiting for approval, owner response, access or escalation. | Shows process bottlenecks. |
| Duplication | Same data or service information maintained in multiple places. | Shows architecture and source-of-truth issues. |
| Staff impact | Staff uncertainty, escalation, lack of confidence or difficulty resolving enquiries. | Shows operational service impact. |
| Customer impact | Repeat contact, inconsistent answers, delayed service or incorrect advice. | Shows customer experience impact. |
| Omnichannel blocker | Untrusted data, unowned knowledge or inconsistent content. | Shows why foundational investment is needed. |

## Review questions

- What current work would continue even if tools changed?
- What current work exists only because ownership is unclear?
- What current work exists only because systems do not support workflow?
- What current work exists because information is duplicated?
- What current work should be prevented upstream?
- What current work should remain human-led?
- What current work could be supported by automation or workflow tooling?
- What work creates the strongest business case evidence?
- What governance is needed before content or data can be reused across channels?
- What future capability is genuinely supported by current-state evidence?

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
