# CDSS-SOP-007: Escalate Data Quality or System Issues

## SOP metadata

| Field | Value |
|---|---|
| SOP ID | CDSS-SOP-007 |
| Function | Customer Data and Systems Support |
| SOP name | Escalate data quality or system issues |
| Status | Draft current-state |
| Version | 0.1 |
| Current owner | To validate |
| Maintainer | To validate |
| Reviewer | To validate |
| Date mapped | YYYY-MM-DD |
| Last updated | YYYY-MM-DD |

## 1. Purpose

This SOP documents the current-state process for escalating customer data quality or system issues that cannot be resolved directly by the Customer Data and Systems Support function.

The purpose is to understand when issues are escalated, who they are escalated to, what information is provided and how follow-up is tracked.

This SOP should be validated with the officer who performs the work before it is treated as confirmed current practice.

## 2. Scope

## In scope

- escalating unclear customer data quality issues
- escalating high-risk or sensitive customer record issues
- escalating CRM or related system constraints
- escalating access or permission issues
- recording escalated items
- tracking unresolved escalations
- confirming outcomes where required

## Out of scope

- enterprise incident management design
- formal system administration procedures
- system configuration changes
- privacy investigation procedures
- broad CX reporting or analysis
- final operating model escalation governance

## 3. Trigger

This process may start when:

| Trigger | Description | Status |
|---|---|---|
| Data issue cannot be resolved | Officer cannot confidently correct, cleanse or de-duplicate a record. | To validate |
| Case is sensitive or high risk | Issue may create privacy, compliance or customer impact risk. | To validate |
| System blocks the required action | CRM or related system does not allow the correction or merge. | To validate |
| Officer lacks access or permission | Required action is outside current system permissions. | To validate |
| Ownership is unclear | It is unclear which team or person should resolve the issue. | To validate |
| Work instruction does not cover the case | Existing guidance is missing, incomplete or unclear. | To validate |

## 4. Inputs required

| Input | Required? | Source | Notes |
|---|---|---|---|
| Issue description | Yes | Officer assessment | Describe the problem without unnecessary personal information. |
| Customer record reference | To validate | CRM / Salesforce / Pathway | Use reference only where possible. |
| Reason for escalation | Yes | Officer assessment | Explain why the issue cannot be resolved directly. |
| Supporting evidence | To validate | System record / screenshot / notes / request | Avoid sensitive information where possible. |
| Proposed escalation owner | To validate | Manager / system owner / team | Confirm pathway. |
| Current status | Yes | Tracker / system note / email | Pending, escalated, resolved or unresolved. |

## 5. Current process

Draft process to validate:

1. Identify that the data quality or system issue cannot be resolved directly.
2. Determine why escalation is required.
3. Check whether the issue relates to:
   - unclear data
   - conflicting information
   - sensitive or high-risk record
   - access limitation
   - system constraint
   - unclear ownership
   - missing work instruction
4. Identify the likely escalation owner.
5. Prepare a concise issue summary.
6. Include only the information needed to explain the issue.
7. Escalate through the current agreed channel.
8. Record the escalation using the current tracking method.
9. Monitor or follow up as required.
10. Record the outcome once resolved, returned or closed.

## 6. Decision points

| Decision | How the decision is made today | Source of rule | Status |
|---|---|---|---|
| Does this issue require escalation? | Assess whether the issue is unclear, risky, outside authority or system-constrained. | To validate | Draft |
| What type of escalation is this? | Classify as data quality, privacy/sensitivity, access, system, ownership or guidance issue. | To validate | Draft |
| Who should the issue go to? | Identify manager, system owner, service area or support pathway. | To validate | Draft |
| What information should be included? | Provide enough context without unnecessary sensitive details. | To validate | Draft |
| How should follow-up be tracked? | Use tracker, email, system note or queue. | To validate | Draft |
| When is escalation considered resolved? | Confirm outcome, action taken or next step. | To validate | Draft |

## 7. Systems and tools

| System or tool | Used for | Notes |
|---|---|---|
| Salesforce | Identifying issue and record reference. | Confirm actual use. |
| Pathway | Checking related customer or service information. | Confirm actual use. |
| Email | Sending escalation or requesting clarification. | Confirm actual use. |
| Teams | Informal clarification or escalation. | Confirm actual use. |
| Service desk or ticketing tool | Raising system issues. | Confirm if used. |
| Spreadsheet or tracker | Tracking escalation status. | Confirm if used. |
| Work instruction | Identifying escalation criteria or owner. | Confirm existence and location. |

## 8. Exception types

| Exception | What happens today | Risk or impact | Status |
|---|---|---|---|
| Escalation owner is unclear. | To validate. | Issue may be delayed or bounced between teams. | Open |
| Issue contains sensitive information. | To validate. | Privacy or information handling risk. | Open |
| No response is received. | To validate. | Issue may remain unresolved. | Open |
| Escalation pathway is informal. | To validate. | Inconsistent handling and traceability risk. | Open |
| System issue affects multiple records. | To validate. | Larger operational impact may not be visible. | Open |
| The issue is returned without resolution. | To validate. | Rework or unresolved data issue. | Open |

## 9. Controls

| Control | Purpose | Status |
|---|---|---|
| Escalation criteria | Clarify when an issue should be escalated. | To validate |
| Issue classification | Helps route the issue to the right owner. | To validate |
| Minimum information standard | Ensures escalation includes enough detail. | To validate |
| Privacy-safe summary | Reduces unnecessary exposure of personal information. | To validate |
| Escalation record | Supports traceability. | To validate |
| Follow-up check | Prevents unresolved escalations from being lost. | To validate |
| Outcome record | Confirms what happened after escalation. | To validate |

## 10. Handoffs

| From | To | What is handed over | Method | Status |
|---|---|---|---|---|
| Customer Data and Systems Support | Manager | Unclear or high-risk data quality issue. | To validate | Open |
| Customer Data and Systems Support | System owner or administrator | CRM issue, access issue or system constraint. | To validate | Open |
| Customer Data and Systems Support | Technology support | Technical issue requiring system support. | To validate | Open |
| Customer Data and Systems Support | Relevant service area | Issue requiring business context or source confirmation. | To validate | Open |

## 11. Pain points and risks

| Pain point or risk | Impact | Status |
|---|---|---|
| Escalation rules may be informal or unclear. | Inconsistent escalation and reliance on individual knowledge. | To validate |
| Ownership may be unclear. | Delay, rework or unresolved issues. | To validate |
| Escalations may be tracked manually. | Visibility and continuity risk. | To validate |
| Sensitive details may be shared unnecessarily. | Privacy and information handling risk. | To validate |
| System issues may not be connected to root causes. | Recurring operational friction. | To validate |

## 12. Omnichannel implications

Escalation pathways matter for omnichannel readiness because unresolved data and system issues can affect customer recognition, context and service continuity across channels.

Current-state observations may inform future requirements such as:

- clear ownership of customer data quality issues
- standard escalation pathways
- privacy-safe issue summaries
- visible unresolved issue queues
- system support triage rules
- root cause analysis of recurring data issues
- defined human review points for ambiguous customer identity cases

## 13. Open questions

- What types of issues are escalated most often?
- Who are data quality issues escalated to?
- Who are system issues escalated to?
- What channel is used for escalation?
- How are escalations tracked?
- How are unresolved escalations followed up?
- What information must be included in an escalation?
- What information should not be included?
- What issues are often bounced between owners?
- What escalation pathways are informal?
- What issues indicate future governance gaps?

## 14. Validation notes

| Date | Validated with | Changes made | Open issues |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |
