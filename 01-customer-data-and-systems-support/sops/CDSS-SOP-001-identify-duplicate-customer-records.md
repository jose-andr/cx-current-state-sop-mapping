# CDSS-SOP-001: Identify Duplicate Customer Records

## SOP metadata

| Field | Value |
|---|---|
| SOP ID | CDSS-SOP-001 |
| Function | Customer Data and Systems Support |
| SOP name | Identify duplicate customer records |
| Status | Draft current-state |
| Version | 0.1 |
| Current owner | To validate |
| Maintainer | To validate |
| Reviewer | To validate |
| Date mapped | YYYY-MM-DD |
| Last updated | YYYY-MM-DD |

## 1. Purpose

This SOP documents the current-state process for identifying possible duplicate customer records.

The purpose is to understand how duplicate records are detected today, what information is used to assess them, and what decision points, exceptions and risks exist in the process.

This SOP should be validated with the officer who performs the work before it is treated as confirmed current practice.

## 2. Scope

## In scope

- identifying possible duplicate customer records
- reviewing records flagged as potential duplicates
- checking available customer information
- deciding whether records require further review
- recording or tracking duplicate candidates
- escalating unclear or risky duplicate cases

## Out of scope

- final merge or de-duplication decisions
- broader CRM reporting and analysis
- customer experience measurement
- system configuration changes
- automated duplicate matching rule design
- approved future-state process design

## 3. Trigger

This process may start when:

| Trigger | Description | Status |
|---|---|---|
| System query or report | A CRM or related system query identifies possible duplicate records. | To validate |
| Manual search | Officer identifies possible duplicate records during customer record review. | To validate |
| Staff request | Another staff member reports a suspected duplicate. | To validate |
| Data quality activity | Duplicate review is part of broader data cleansing work. | To validate |
| System alert or queue | A system-generated task or alert identifies possible duplicates. | To validate |

## 4. Inputs required

| Input | Required? | Source | Notes |
|---|---|---|---|
| Customer name or entity name | To validate | CRM / Salesforce / Pathway | Used to compare records. |
| Contact details | To validate | CRM / Salesforce / Pathway | May include phone, email or address. |
| Customer ID or account reference | To validate | CRM / Salesforce / Pathway | Used to distinguish or match records. |
| Interaction or case history | To validate | CRM or related system | May help confirm whether records relate to the same customer. |
| Duplicate search result or query output | To validate | CRM / report / manual search | May provide candidate records. |
| Work instruction or matching criteria | To validate | Local guidance / officer knowledge | Confirm whether documented. |

## 5. Current process

Draft process to validate:

1. Open the relevant CRM or customer data system.
2. Run the duplicate search, query, report or review method used for the activity.
3. Review the returned customer records.
4. Compare available identifiers and contact details.
5. Check whether the records appear to represent the same customer, account or entity.
6. Classify the record pair or group as:
   - likely duplicate
   - possible duplicate requiring further review
   - not a duplicate
   - unclear or risky case requiring escalation
7. Record the outcome using the current tracking method.
8. Escalate unclear, sensitive or system-constrained cases where required.
9. Move confirmed duplicate candidates to the next appropriate process, such as manual de-duplication or data correction.

## 6. Decision points

| Decision | How the decision is made today | Source of rule | Status |
|---|---|---|---|
| Is this a possible duplicate? | Compare available customer identifiers and record details. | To validate | Draft |
| Are the records likely to be the same customer or entity? | Review name, contact details, account references or interaction history. | To validate | Draft |
| Is there enough information to continue? | Check whether required identifiers or evidence are available. | To validate | Draft |
| Does the case need escalation? | Escalate if identity is unclear, information conflicts or risk is high. | To validate | Draft |
| How should the candidate duplicate be recorded? | Use current tracker, queue or system note. | To validate | Draft |

## 7. Systems and tools

| System or tool | Used for | Notes |
|---|---|---|
| Salesforce | Reviewing and identifying possible duplicate customer records. | Confirm actual use. |
| Pathway | Reviewing related customer or service information. | Confirm actual use. |
| Spreadsheet or tracker | Tracking duplicate candidates or progress. | Confirm if used. |
| Work instruction | Guiding duplicate identification criteria. | Confirm existence and location. |
| Email or Teams | Escalating or clarifying unclear cases. | Confirm actual pathway. |

## 8. Exceptions

| Exception | What happens today | Risk or impact | Status |
|---|---|---|---|
| Records look similar but may not be the same customer. | To validate. | Risk of incorrect merge or unresolved duplicate. | Open |
| Records contain conflicting contact details. | To validate. | Unclear which information is reliable. | Open |
| Required identifying information is missing. | To validate. | Review may be delayed or escalated. | Open |
| System search returns too many possible matches. | To validate. | Manual review effort increases. | Open |
| Case appears sensitive or high risk. | To validate. | Privacy or customer impact risk. | Open |
| Work instruction does not cover the scenario. | To validate. | Officer judgment or escalation required. | Open |

## 9. Controls

| Control | Purpose | Status |
|---|---|---|
| Record comparison | Reduce risk of incorrect duplicate classification. | To validate |
| Required information check | Confirm there is enough evidence to continue. | To validate |
| Escalation threshold | Ensure unclear or risky cases are reviewed. | To validate |
| Progress tracking | Maintain visibility of reviewed and unresolved candidates. | To validate |
| Completion note or record | Support traceability of work completed. | To validate |

## 10. Handoffs

| From | To | What is handed over | Method | Status |
|---|---|---|---|---|
| Customer Data and Systems Support | To validate | Candidate duplicate records requiring review or action. | To validate | Open |
| Customer Data and Systems Support | Manager or system owner | Unclear, risky or system-constrained duplicate cases. | To validate | Open |
| Staff member or team | Customer Data and Systems Support | Suspected duplicate record issue. | To validate | Open |

## 11. Pain points and risks

| Pain point or risk | Impact | Status |
|---|---|---|
| Duplicate criteria may be undocumented. | Inconsistent decisions or reliance on individual knowledge. | To validate |
| Duplicate review may be manual and time-consuming. | Staff effort and delay. | To validate |
| Missing or conflicting information may block review. | Rework, escalation or unresolved records. | To validate |
| Incorrect duplicate identification could lead to incorrect merge. | Data integrity, privacy and customer impact risk. | To validate |
| Unresolved duplicates may fragment customer context. | Reduced service consistency across channels. | To validate |

## 12. Omnichannel implications

Identifying duplicate customer records is important for future omnichannel service delivery because customer context depends on reliable customer identity.

Current-state observations may inform future requirements such as:

- standard identity matching rules
- duplicate prevention at intake
- required customer identifiers
- confidence thresholds for duplicate detection
- human review points for ambiguous matches
- workflow visibility for unresolved duplicate candidates
- audit trail requirements for customer record changes

## 13. Open questions

- What system or report is used to identify duplicate records?
- How often is duplicate identification performed?
- What fields are used to compare records?
- What makes a record a likely duplicate?
- What makes a case too risky to action without escalation?
- Where are possible duplicates tracked?
- Who reviews unresolved duplicate candidates?
- What happens after a duplicate candidate is identified?
- Are there written matching rules or work instructions?
- What upstream channels or processes create duplicates?

## 14. Validation notes

| Date | Validated with | Changes made | Open issues |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |
