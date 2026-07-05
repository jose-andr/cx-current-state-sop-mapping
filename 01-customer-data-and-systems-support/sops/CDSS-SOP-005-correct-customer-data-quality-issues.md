# CDSS-SOP-005: Correct Customer Data Quality Issues

## SOP metadata

| Field | Value |
|---|---|
| SOP ID | CDSS-SOP-005 |
| Function | Customer Data and Systems Support |
| SOP name | Correct customer data quality issues |
| Status | Draft current-state |
| Version | 0.1 |
| Current owner | To validate |
| Maintainer | To validate |
| Reviewer | To validate |
| Date mapped | YYYY-MM-DD |
| Last updated | YYYY-MM-DD |

## 1. Purpose

This SOP documents the current-state process for correcting customer data quality issues.

The purpose is to understand how inaccurate, incomplete, outdated, duplicated or inconsistent customer data is corrected today, including what rules, evidence, permissions and escalation pathways are used.

This SOP should be validated with the officer who performs the work before it is treated as confirmed current practice.

## 2. Scope

## In scope

- reviewing customer data quality issues
- confirming whether correction is required
- identifying the correct source information
- correcting permitted customer data fields
- recording completed corrections
- escalating unclear, sensitive or system-constrained issues

## Out of scope

- broad customer experience reporting
- data governance framework design
- system configuration changes
- automated correction rules
- large-scale data migration
- customer-facing communication unless directly required by the correction process

## 3. Trigger

This process may start when:

| Trigger | Description | Status |
|---|---|---|
| Data quality issue identified | A record is found to contain inaccurate, incomplete, outdated or inconsistent data. | To validate |
| Duplicate review | Correction is required after reviewing duplicate records. | To validate |
| Staff request | A staff member requests correction of customer data. | To validate |
| System report or query | A report, queue or query identifies records requiring correction. | To validate |
| Manual discovery | The officer identifies an issue while completing related work. | To validate |
| Escalated issue | Another person or team escalates a customer data issue. | To validate |

## 4. Inputs required

| Input | Required? | Source | Notes |
|---|---|---|---|
| Customer record | Yes | CRM / Salesforce / Pathway | Record requiring correction. |
| Description of issue | Yes | System, officer, staff request or report | Explains what appears incorrect or incomplete. |
| Correct source information | To validate | CRM / related system / approved source | Required before changing customer data. |
| Correction rule or work instruction | To validate | Work instruction / policy / officer knowledge | Confirm whether documented. |
| System access or permission | Yes | CRM / related system | Required to make correction. |
| Escalation contact | Conditional | Manager / system owner / relevant team | Needed for unclear or restricted corrections. |

## 5. Current process

Draft process to validate:

1. Receive or identify the customer data quality issue.
2. Open the relevant customer record.
3. Review the issue and determine what appears inaccurate, incomplete, outdated or inconsistent.
4. Check available source information.
5. Confirm whether there is enough evidence to correct the record.
6. Determine whether the officer has authority and system access to make the correction.
7. If correction is permitted, update the relevant customer data field or record.
8. Record the correction or update progress according to current practice.
9. If correction is not permitted or the correct action is unclear, escalate the issue.
10. Mark the issue as complete, pending, escalated or unresolved using the current tracking method.

## 6. Decision points

| Decision | How the decision is made today | Source of rule | Status |
|---|---|---|---|
| What is the data quality issue? | Review the record and classify the issue. | To validate | Draft |
| Is the source information reliable? | Compare available sources or evidence. | To validate | Draft |
| Is there enough evidence to correct the record? | Check whether required information is present. | To validate | Draft |
| Can the officer make the correction? | Check system permission, authority and risk. | To validate | Draft |
| Does the issue require escalation? | Escalate if information is unclear, sensitive, conflicting or outside authority. | To validate | Draft |
| How should the correction be recorded? | Use system note, tracker, task status or current method. | To validate | Draft |

## 7. Systems and tools

| System or tool | Used for | Notes |
|---|---|---|
| Salesforce | Reviewing and correcting customer records. | Confirm actual use. |
| Pathway | Checking related customer or service information. | Confirm actual use. |
| Spreadsheet or tracker | Tracking corrections and unresolved issues. | Confirm if used. |
| Work instruction | Guiding correction decisions. | Confirm existence and location. |
| Email or Teams | Clarifying or escalating issues. | Confirm actual pathway. |

## 8. Exceptions

| Exception | What happens today | Risk or impact | Status |
|---|---|---|---|
| Correct information cannot be confirmed. | To validate. | Correction may be delayed or blocked. | Open |
| Sources contain conflicting information. | To validate. | Officer may not know which source is reliable. | Open |
| Officer does not have permission to change the field. | To validate. | Handoff or escalation required. | Open |
| Change may affect privacy or customer outcome. | To validate. | High-risk correction requiring review. | Open |
| System does not allow the required correction. | To validate. | Workaround or escalation required. | Open |
| Issue is caused by upstream process. | To validate. | Correction may not prevent recurrence. | Open |
| Work instruction does not cover the issue. | To validate. | Officer judgment or manager advice required. | Open |

## 9. Controls

| Control | Purpose | Status |
|---|---|---|
| Issue classification | Clarify what type of data quality issue exists. | To validate |
| Source information check | Confirm correct information before changing data. | To validate |
| Required evidence check | Prevent unsupported corrections. | To validate |
| Permission check | Confirm the officer can make the correction. | To validate |
| Privacy or sensitivity check | Prevent inappropriate or risky correction. | To validate |
| Escalation threshold | Ensure unclear or high-risk cases are reviewed. | To validate |
| Completion record | Support traceability of completed corrections. | To validate |

## 10. Handoffs

| From | To | What is handed over | Method | Status |
|---|---|---|---|---|
| Staff member or team | Customer Data and Systems Support | Customer data issue requiring correction. | To validate | Open |
| Customer Data and Systems Support | Manager or system owner | Unclear, sensitive or restricted correction issue. | To validate | Open |
| Customer Data and Systems Support | Technology or system support | Issue blocked by system limitation or access. | To validate | Open |
| Customer Data and Systems Support | Relevant service area | Issue requiring source confirmation or business context. | To validate | Open |

## 11. Pain points and risks

| Pain point or risk | Impact | Status |
|---|---|---|
| Correct source information may be difficult to confirm. | Delay, uncertainty and rework. | To validate |
| Correction rules may be undocumented. | Inconsistent handling and reliance on individual knowledge. | To validate |
| System permissions may limit correction. | Handoffs and unresolved issues. | To validate |
| Incorrect correction may affect customer context. | Service quality, privacy and data integrity risk. | To validate |
| Completed corrections may not be fully traceable. | Audit and continuity risk. | To validate |
| Upstream causes may remain unresolved. | Recurring data quality issues. | To validate |

## 12. Omnichannel implications

Customer data correction is foundational to future omnichannel service delivery.

Current-state observations may inform future requirements such as:

- source-of-truth rules
- required customer identifiers
- correction authority thresholds
- privacy and sensitivity checks
- human review thresholds for data changes
- visible unresolved issue queues
- audit trail expectations
- upstream validation and duplicate prevention
- clearer ownership of customer data quality

## 13. Open questions

- What types of customer data issues are corrected most often?
- What fields can the officer correct?
- What fields require escalation?
- What source information is considered reliable?
- What happens when source information conflicts?
- What permissions does the officer have?
- What privacy or sensitivity rules apply?
- How are completed corrections recorded?
- How are unresolved issues tracked?
- Who owns issues that cannot be corrected by the officer?
- What upstream processes create recurring correction work?

## 14. Validation notes

| Date | Validated with | Changes made | Open issues |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |
