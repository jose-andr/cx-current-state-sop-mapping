# Decision Points

## Function

Customer Data and Systems Support

## Purpose

This file captures the decisions made during Customer Data and Systems Support work.

Decision points are important because they show where the officer applies rules, judgment, system knowledge or escalation criteria.

They also reveal what needs to be documented, governed or automated in future.

## Current status

Status: Draft discovery placeholder.

Decision points should be validated with the officer who performs the work.

## Decision point inventory

| Decision ID | Decision | Work activity | How the decision is made today | Source of rule | Confidence | Notes |
|---|---|---|---|---|---|---|
| D-001 | Is this a possible duplicate customer record? | Identify duplicate customer records | To validate | System rule / search result / officer judgment | Low | Confirm duplicate matching criteria. |
| D-002 | Are the records definitely the same customer or entity? | Review duplicate candidates | To validate | Work instruction / officer judgment / data comparison | Low | Confirm required evidence. |
| D-003 | Which record should be retained as the primary record? | Manual de-duplication | To validate | Work instruction / system rule / officer judgment | Low | Important data quality control. |
| D-004 | What data should be kept, corrected or removed? | Cleanse customer records | To validate | Work instruction / data quality standard / privacy rule | Low | Confirm allowed field changes. |
| D-005 | Is there enough information to correct the record? | Correct data quality issues | To validate | Officer judgment / documented criteria | Low | Missing evidence may trigger escalation. |
| D-006 | Can the officer make the correction independently? | Correct data quality issues | To validate | Permission / policy / system access / manager advice | Low | Clarify authority and access limits. |
| D-007 | Does the issue need escalation? | Escalate data quality or system issues | To validate | Risk threshold / system limitation / unclear ownership | Low | Confirm escalation path. |
| D-008 | Has the work been completed and recorded properly? | Record progress of cleansing work | To validate | Tracker / checklist / work instruction | Low | Confirm completion criteria. |

## Decision detail template

Use the following structure to expand each decision.

## Decision: [decision name]

| Attribute | Details |
|---|---|
| Decision ID |  |
| Related SOP |  |
| Decision question |  |
| When this decision occurs |  |
| Inputs required |  |
| Rule or criteria |  |
| Source of rule | Documented / informal / officer judgment / manager advice / policy / system rule |
| Who makes the decision |  |
| Who approves if needed |  |
| Possible outcomes |  |
| Escalation required? | Yes / no / sometimes |
| Risk if wrong |  |
| Current confidence | High / medium / low |
| Notes |  |

## Decision sources

Use this table to identify where decision rules come from.

| Source type | Examples | Reliability |
|---|---|---|
| Documented work instruction | Formal or informal guide used by the officer | To validate |
| System rule | Matching logic, validation rule or permission in CRM | To validate |
| Policy or standard | Privacy, data quality or customer record standards | To validate |
| Manager advice | Direction from manager or program lead | To validate |
| Officer judgment | Experience-based decision-making | To validate |
| Peer advice | Advice from another officer or team member | To validate |
| Historical precedent | “This is how it has usually been done” | To validate |

## Decisions requiring escalation

| Decision | Escalation trigger | Escalation owner | Notes |
|---|---|---|---|
| Whether to merge uncertain records | Records look similar but evidence is incomplete. | To validate |  |
| Whether to change sensitive customer data | Change may have privacy, legal or service implications. | To validate |  |
| Whether a system issue blocks the process | System does not allow required correction or merge. | To validate |  |
| Whether source information is reliable | Conflicting information exists across records or systems. | To validate |  |

## Risks linked to decision points

| Risk | Related decision | Potential impact |
|---|---|---|
| Incorrectly merging two different customers | Are the records definitely the same customer or entity? | Data integrity issue, privacy risk, customer impact. |
| Keeping the wrong primary record | Which record should be retained? | Loss of useful history or incorrect customer context. |
| Correcting data without enough evidence | Is there enough information to correct the record? | Inaccurate records or compliance risk. |
| Failing to escalate unclear cases | Does the issue need escalation? | Inconsistent handling or unresolved data issue. |
| Not recording completed work | Has the work been completed and recorded properly? | Lack of traceability and continuity risk. |

## Omnichannel implications

Decision points are critical for future omnichannel design because customer identity and account context need to be reliable across channels.

| Current decision point | Future implication |
|---|---|
| Determining whether records are duplicates | Future systems may need clearer identity matching logic. |
| Selecting the primary record | Future customer context depends on reliable source-of-truth rules. |
| Correcting customer data | Future self-service and automation require clear correction rules. |
| Escalating unclear records | Future operating model needs defined ownership for ambiguous cases. |
| Recording completed work | Future workflow needs visible status and auditability. |

## Discovery questions

- What decisions do you make during duplicate review?
- What makes two records a true duplicate?
- What information do you compare?
- What information is most reliable?
- What information is least reliable?
- How do you decide which record to keep?
- What are you allowed to change?
- What are you not allowed to change?
- What cases make you stop and ask someone else?
- Who do you ask when unsure?
- What decisions are written down?
- What decisions are based on experience?
- What decision mistakes would create the biggest risk?
- What decisions could be supported by system rules in future?
- What decisions should always stay human-reviewed?

## Review notes

| Date | Update | Updated by |
|---|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
