# Omnichannel Implications

## Function

Customer Data and Systems Support

## Purpose

This file captures what the current-state work reveals about future omnichannel service delivery.

The focus is on customer data quality, customer identity, account context, CRM reliability, system support, workflow visibility and automation readiness.

## Current status

Status: Draft discovery placeholder.

Implications should be validated after current-state SOPs are mapped.

## Why this matters

Omnichannel service depends on customers being recognised consistently across channels.

If customer records are duplicated, incomplete, outdated or difficult to correct, staff and systems may not be able to preserve customer context.

This can lead to:

- customers repeating information
- staff checking multiple records
- fragmented interaction history
- inconsistent service responses
- higher rework
- unreliable automation
- reduced trust in CRM data

## Implication inventory

| ID | Current-state observation | Omnichannel implication | Type | Status |
|---|---|---|---|---|
| OI-001 | Duplicate customer records may exist in CRM or related systems. | Customer identity and history may be fragmented across channels. | Customer identity | To validate |
| OI-002 | Duplicate review may require manual judgment. | Future identity matching may need clear rules, confidence thresholds and human review points. | Data governance | To validate |
| OI-003 | Customer records may contain missing or conflicting information. | Staff and systems may not know which customer context is reliable. | Data quality | To validate |
| OI-004 | Data correction may depend on undocumented experience. | Future automation requires explicit correction rules and decision criteria. | Automation readiness | To validate |
| OI-005 | Some corrections may require escalation. | Future service model needs clear ownership for complex or risky customer data changes. | Operating model | To validate |
| OI-006 | Progress tracking may occur outside the primary system. | Future workflows may need visible task status, ownership and audit trail. | Workflow visibility | To validate |
| OI-007 | Upstream channels or processes may create duplicate records. | Channel design should prevent avoidable data quality issues at intake. | Channel design | To validate |
| OI-008 | Role expectations may exceed current operational practice. | Future capability design must distinguish between existing capacity and desired omnichannel capability. | Capability design | To validate |

## Omnichannel design themes

## 1. Customer identity

Current-state data quality work can reveal whether the organisation has reliable customer identity across systems.

Key questions:

- Can the same customer be recognised across channels?
- Are duplicate records common?
- What fields are used to identify customers?
- Which identifiers are reliable?
- Which identifiers are inconsistent or missing?
- What causes duplicate customer records?

## 2. Customer context

Customer context includes account details, previous interactions, open requests, history and relevant service information.

Key questions:

- What customer context is needed to complete the work?
- Is context available in one place?
- Is context split across systems?
- What happens when context is missing or conflicting?
- What context should carry between channels?

## 3. Data quality at intake

Many downstream data issues may start when information is first collected.

Key questions:

- Which channels create poor-quality customer records?
- What information is missing at intake?
- What validation could prevent later cleansing?
- What fields should be mandatory?
- What format rules are needed?
- What duplicate prevention could happen earlier?

## 4. Human review thresholds

Not every data decision should be automated.

Key questions:

- Which corrections are safe and routine?
- Which corrections require human judgment?
- Which corrections require escalation?
- Which decisions have privacy or customer impact risk?
- What confidence threshold would be needed before automation?

## 5. Workflow visibility

If current work is tracked outside core systems, future operating models may need stronger workflow visibility.

Key questions:

- Where is work status visible today?
- How is completed work recorded?
- How are unresolved issues tracked?
- Who can see pending work?
- What would happen if the officer was unavailable?
- What should be visible in a future workflow?

## 6. Governance and ownership

Data quality work exposes questions of accountability.

Key questions:

- Who owns customer data quality?
- Who owns customer identity rules?
- Who approves risky corrections?
- Who resolves unclear records?
- Who owns upstream causes of duplicate records?
- Who owns system changes that could prevent recurring issues?

## 7. Automation readiness

Automation depends on structured, reliable and governed data.

Key questions:

- Which data quality steps are repeatable?
- Which steps depend on judgment?
- Which rules are documented?
- Which rules are informal?
- Which exceptions are common?
- Which process steps could be automated only after data quality improves?

## Future-state requirement candidates

Use this section to capture possible future requirements.

| Requirement ID | Candidate requirement | Source observation | Status |
|---|---|---|---|
| FR-001 | Define standard customer identity matching rules. | Duplicate records require review. | Candidate |
| FR-002 | Define confidence thresholds for automated duplicate detection. | Some duplicate decisions may require judgment. | Candidate |
| FR-003 | Create a visible queue for unresolved customer data issues. | Exceptions may need tracking. | Candidate |
| FR-004 | Define ownership for high-risk data corrections. | Some corrections may require escalation. | Candidate |
| FR-005 | Improve intake validation to reduce duplicate creation. | Upstream channels may create duplicates. | Candidate |
| FR-006 | Document data correction rules for common scenarios. | Current correction may rely on officer knowledge. | Candidate |
| FR-007 | Create audit trail expectations for customer record changes. | Completed work needs traceability. | Candidate |
| FR-008 | Identify which customer data fields are critical for channel continuity. | Omnichannel depends on reliable context. | Candidate |

## Automation candidate notes

| Candidate | Why it may be suitable | Constraint or caution |
|---|---|---|
| Duplicate detection | Matching rules may identify likely duplicate records. | Human review needed for ambiguous or high-risk matches. |
| Required field validation | Missing information could be prevented at intake. | Field rules need to be agreed with service owners and system owners. |
| Data quality alerts | Records with missing or inconsistent fields could be flagged. | Alerts need ownership and workflow follow-up. |
| Progress tracking | Cleansing tasks could be tracked in a queue or workflow. | Requires clear status model and task ownership. |
| Escalation routing | Certain exception types could route to the right owner. | Escalation rules must be defined and maintained. |

## Business case signals

Capture evidence that may support a future operating model or investment case.

| Signal | Why it matters |
|---|---|
| Customer data quality affects channel continuity. | Omnichannel service requires reliable customer context. |
| Duplicate records create operational effort. | Reducing duplicates may reduce staff effort and rework. |
| Manual correction rules may be undocumented. | Standardisation is needed before safe automation. |
| Exceptions require escalation. | Future governance and ownership need clarification. |
| Upstream channels may create data issues. | Service and channel design should prevent avoidable downstream work. |
| Role intent may exceed current practice. | Capability design may need more than position description changes. |

## Review questions

- Which current data quality issues affect customer experience directly?
- Which issues affect staff effort?
- Which issues affect CRM trust?
- Which issues affect future channel continuity?
- Which issues would block automation?
- Which issues are caused upstream?
- Which issues require governance rather than just process improvement?
- Which issues should become business case evidence?

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
