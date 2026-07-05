# Exception Pathways

## Function

Customer Data and Systems Support

## Purpose

This file captures exceptions that occur when Customer Data and Systems Support work does not follow a standard path.

Exceptions are important because they reveal hidden complexity, risk, system constraints, unclear ownership and future automation limits.

## Current status

Status: Draft discovery placeholder.

Exception pathways should be validated with the officer who performs the work.

## Exception inventory

| Exception ID | Exception | Related work activity | What happens today | Impact | Status |
|---|---|---|---|---|---|
| E-001 | Possible duplicate records are not clearly the same customer | Duplicate record review | To validate | Risk of incorrect merge or unresolved duplicate. | Open |
| E-002 | Records contain conflicting information | Customer record cleansing | To validate | Officer may not know which information is correct. | Open |
| E-003 | Required information is missing | Data correction | To validate | Correction may be paused, delayed or escalated. | Open |
| E-004 | System does not allow the required correction | CRM data maintenance | To validate | Manual workaround or escalation may be required. | Open |
| E-005 | Customer record contains sensitive or high-risk information | Data correction or de-duplication | To validate | Privacy, compliance or customer impact risk. | Open |
| E-006 | Ownership of the record or issue is unclear | Escalation | To validate | Delay, rework or unresolved issue. | Open |
| E-007 | Duplicate appears to be caused by upstream process or channel | Duplicate identification | To validate | Root cause may remain unresolved. | Open |
| E-008 | Work instructions do not cover the case | Any SOP | To validate | Officer judgment or manager advice required. | Open |

## Exception detail template

Use the following structure to expand each exception.

## Exception: [exception name]

| Attribute | Details |
|---|---|
| Exception ID |  |
| Related SOP |  |
| Where it occurs |  |
| How it is identified |  |
| What happens today |  |
| Who decides what to do |  |
| Escalation required? | Yes / no / sometimes |
| Escalation path |  |
| Workaround used |  |
| Risk or impact |  |
| Current control |  |
| Future-state implication |  |
| Status | Open / confirmed / resolved / superseded |

## Common exception types

| Exception type | Description | Example |
|---|---|---|
| Missing information | Required information is absent or incomplete. | Customer record does not contain enough detail to confirm a duplicate. |
| Conflicting information | Different systems or records show different details. | Two records have similar names but different contact details. |
| Ambiguous identity | It is unclear whether records belong to the same customer or entity. | Similar business names with different addresses. |
| System constraint | The system prevents or complicates the required action. | Field cannot be edited or records cannot be merged. |
| Access constraint | The officer does not have permission to complete the action. | Required field or merge function is not available to the role. |
| Policy or privacy concern | The action may have compliance implications. | Sensitive information may be exposed or incorrectly linked. |
| Ownership ambiguity | It is unclear who should resolve the issue. | Data issue appears to belong to another team or system owner. |
| Work instruction gap | Existing instructions do not explain what to do. | No guidance for a particular duplicate scenario. |

## Escalation pathways

Use this section to capture how exceptions are escalated.

| Exception | Escalated to | When to escalate | How to escalate | Expected response |
|---|---|---|---|---|
| Unclear duplicate match | To validate | Evidence is insufficient or conflicting. | To validate | To validate |
| Sensitive data correction | To validate | Correction may affect privacy, compliance or customer outcome. | To validate | To validate |
| System limitation | To validate | CRM or related system prevents required action. | To validate | To validate |
| Unclear ownership | To validate | Officer cannot determine responsible team or owner. | To validate | To validate |
| Missing work instruction | To validate | Existing guidance does not cover the situation. | To validate | To validate |

## Workarounds

Use this section to capture manual or informal methods used to handle exceptions.

| Workaround | Used when | Why it exists | Risk | Future implication |
|---|---|---|---|---|
| Manual tracking outside CRM | To validate | System may not support progress visibility. | Traceability and continuity risk. | Future workflow may need built-in status tracking. |
| Informal advice from manager or colleague | To validate | Decision rule may not be documented. | Inconsistent handling risk. | Decision rules may need formalisation. |
| Leaving record unresolved | To validate | Evidence or authority may be insufficient. | Data quality issue remains. | Future process may need unresolved-case queue. |

## Risks created by exceptions

| Risk | Related exception | Potential impact |
|---|---|---|
| Incorrect record merge | Ambiguous identity | Customer data integrity, privacy and service quality risk. |
| Incorrect data correction | Missing or conflicting information | Inaccurate customer context. |
| Unresolved duplicate records | System constraint or unclear ownership | Poor omnichannel context and repeat staff effort. |
| Inconsistent handling | Work instruction gap | Different outcomes depending on officer knowledge. |
| Poor traceability | Manual workaround | Hard to know what was done, why and by whom. |

## Omnichannel implications

Exceptions are especially important for future omnichannel design because unresolved data issues can affect customer identity and context across channels.

| Exception pattern | Omnichannel implication |
|---|---|
| Ambiguous customer identity | Customers may not be recognised consistently across channels. |
| Duplicate records remain unresolved | Customer history and context may be fragmented. |
| Conflicting information exists across systems | Staff and systems may provide inconsistent service. |
| Corrections require manual judgment | Automation needs clear rules and human review thresholds. |
| Exceptions are not tracked centrally | Future service model may lack visibility of unresolved data issues. |

## Discovery questions

- What cases do not follow the normal process?
- What makes a duplicate difficult to resolve?
- What information is usually missing?
- What information is often conflicting?
- What cases make you stop and ask someone else?
- What system limitations create exceptions?
- What access limitations create exceptions?
- What workarounds do you use?
- What exceptions happen repeatedly?
- What exceptions create the greatest risk?
- What exceptions create the most delay?
- What exceptions should be prevented upstream?
- What exceptions should have a clearer escalation path?
- What exceptions should never be automated?

## Review notes

| Date | Update | Updated by |
|---|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
