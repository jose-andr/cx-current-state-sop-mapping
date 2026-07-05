# CDSS-SOP-003: Manually De-duplicate Customer Records

## SOP metadata

| Field | Value |
|---|---|
| SOP ID | CDSS-SOP-003 |
| Function | Customer Data and Systems Support |
| SOP name | Manually de-duplicate customer records |
| Status | Draft current-state |
| Version | 0.1 |
| Current owner | To validate |
| Maintainer | To validate |
| Reviewer | To validate |
| Date mapped | YYYY-MM-DD |
| Last updated | YYYY-MM-DD |

## 1. Purpose

This SOP documents the current-state process for manually reviewing and resolving duplicate customer records.

The purpose is to understand how duplicate records are assessed, what rules or judgment are used, what information is retained, and what controls are needed to reduce data integrity, privacy and customer experience risk.

This SOP should be validated with the officer who performs the work before it is treated as confirmed current practice.

## 2. Scope

## In scope

- reviewing confirmed or suspected duplicate records
- comparing customer record details
- deciding whether records can be manually de-duplicated
- identifying the primary record
- determining what information should be retained
- completing permitted manual de-duplication steps
- recording work completed
- escalating unclear, risky or system-constrained cases

## Out of scope

- automated de-duplication rule design
- system configuration
- large-scale data migration
- final data governance policy
- broader customer experience reporting or analysis
- de-duplication actions not permitted by the officer’s access or authority

## 3. Trigger

This process may start when:

| Trigger | Description | Status |
|---|---|---|
| Duplicate candidate identified | A possible duplicate has been identified through search, query or review. | To validate |
| Staff request | Another staff member reports duplicate records. | To validate |
| Cleansing activity | Manual de-duplication is part of a broader data quality task. | To validate |
| System limitation | Automated or tool-supported de-duplication is not sufficient. | To validate |
| Exception review | A duplicate case requires manual review due to ambiguity or risk. | To validate |

## 4. Inputs required

| Input | Required? | Source | Notes |
|---|---|---|---|
| Duplicate candidate records | Yes | CRM / Salesforce / Pathway | Records requiring review. |
| Customer identifiers | To validate | CRM / related systems | May include name, address, email, phone, customer ID or account reference. |
| Interaction or case history | To validate | CRM / related systems | May help determine primary record. |
| Source evidence | To validate | System record / staff input / approved source | Used to confirm correct information. |
| De-duplication work instruction | To validate | Local guidance / policy / officer knowledge | Confirm whether documented. |
| System permissions | Yes | CRM / Salesforce / Pathway | Required to complete manual action. |

## 5. Current process

Draft process to validate:

1. Open the duplicate candidate records.
2. Review available identifiers and record details.
3. Compare names, contact details, addresses, account references and interaction history.
4. Decide whether the records represent the same customer, account or entity.
5. If the records are not duplicates, record the outcome and stop the de-duplication process.
6. If the records are likely duplicates, determine whether manual de-duplication is permitted.
7. Identify which record should be retained as the primary record.
8. Identify what information should be kept, corrected, transferred or removed.
9. Complete permitted manual de-duplication steps in the relevant system.
10. Record the work completed using the current tracking method.
11. Escalate any unclear, sensitive, conflicting or system-constrained cases.

## 6. Decision points

| Decision | How the decision is made today | Source of rule | Status |
|---|---|---|---|
| Are these records definitely duplicates? | Compare identifiers, contact details and history. | To validate | Draft |
| Is manual de-duplication allowed? | Check access, authority, system rules and risk. | To validate | Draft |
| Which record should be retained? | Determine primary record based on completeness, currency or system criteria. | To validate | Draft |
| What information should be retained? | Compare record details and identify reliable information. | To validate | Draft |
| Does this case require escalation? | Escalate if identity is unclear, information conflicts or risk is high. | To validate | Draft |
| How should the completed work be recorded? | Use system note, tracker or current completion method. | To validate | Draft |

## 7. Systems and tools

| System or tool | Used for | Notes |
|---|---|---|
| Salesforce | Reviewing and manually resolving duplicate records. | Confirm actual use. |
| Pathway | Checking related customer or service information. | Confirm actual use. |
| Spreadsheet or tracker | Tracking de-duplication progress and unresolved cases. | Confirm if used. |
| Work instruction | Guiding manual de-duplication decisions. | Confirm existence and location. |
| Email or Teams | Escalating or clarifying unclear cases. | Confirm actual pathway. |

## 8. Exceptions

| Exception | What happens today | Risk or impact | Status |
|---|---|---|---|
| Records may belong to different customers. | To validate. | Incorrect merge risk. | Open |
| Records contain conflicting information. | To validate. | Unclear which information should be retained. | Open |
| Primary record is unclear. | To validate. | Incorrect customer context may be retained. | Open |
| System prevents manual de-duplication. | To validate. | Escalation or workaround required. | Open |
| Officer lacks permission to complete action. | To validate. | Handoff required. | Open |
| Record contains sensitive information. | To validate. | Privacy or compliance risk. | Open |
| Work instruction does not cover scenario. | To validate. | Officer judgment or manager advice required. | Open |

## 9. Controls

| Control | Purpose | Status |
|---|---|---|
| Record comparison | Confirm whether records are true duplicates. | To validate |
| Primary record selection check | Reduce risk of retaining the wrong record. | To validate |
| Information retention check | Confirm what data should be kept or corrected. | To validate |
| Permission check | Confirm officer can complete the action. | To validate |
| Privacy or sensitivity check | Prevent inappropriate linking or disclosure. | To validate |
| Escalation threshold | Ensure unclear or high-risk cases are reviewed. | To validate |
| Completion record | Support traceability of de-duplication work. | To validate |

## 10. Handoffs

| From | To | What is handed over | Method | Status |
|---|---|---|---|---|
| Customer Data and Systems Support | Manager or system owner | Unclear or high-risk duplicate case. | To validate | Open |
| Customer Data and Systems Support | System support or administrator | Case blocked by permissions or system constraints. | To validate | Open |
| Staff member or team | Customer Data and Systems Support | Suspected duplicate requiring review. | To validate | Open |

## 11. Pain points and risks

| Pain point or risk | Impact | Status |
|---|---|---|
| Manual de-duplication depends on judgment. | Variation and knowledge dependency. | To validate |
| Primary record selection rules may be unclear. | Risk of retaining incomplete or incorrect customer context. | To validate |
| Incorrect merge could link different customers. | Privacy, data integrity and customer impact risk. | To validate |
| System limitations may prevent clean resolution. | Manual workaround or unresolved duplicate. | To validate |
| Completed work may not be fully traceable. | Audit and continuity risk. | To validate |

## 12. Omnichannel implications

Manual de-duplication is directly connected to omnichannel readiness.

If duplicate customer records remain unresolved, customer history, account context and service interactions may be fragmented across channels.

Current-state observations may inform future requirements such as:

- customer identity matching rules
- primary record selection rules
- trusted source hierarchy
- human review thresholds
- duplicate prevention at intake
- escalation ownership for ambiguous customer identity
- visible unresolved duplicate queues
- audit trail expectations for merged or corrected records

## 13. Open questions

- What makes two records safe to merge?
- What fields are compared before manual de-duplication?
- How is the primary record selected?
- What information is retained from secondary records?
- What information is removed or ignored?
- What cases require escalation?
- What permissions are needed to complete the process?
- What system limitations affect manual de-duplication?
- How is completed work tracked?
- What happens when records cannot be confidently resolved?

## 14. Validation notes

| Date | Validated with | Changes made | Open issues |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |
