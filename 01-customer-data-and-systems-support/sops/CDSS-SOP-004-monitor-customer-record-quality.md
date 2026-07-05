# CDSS-SOP-004: Monitor Customer Record Quality

## SOP metadata

| Field | Value |
|---|---|
| SOP ID | CDSS-SOP-004 |
| Function | Customer Data and Systems Support |
| SOP name | Monitor customer record quality |
| Status | Draft current-state |
| Version | 0.1 |
| Current owner | To validate |
| Maintainer | To validate |
| Reviewer | To validate |
| Date mapped | YYYY-MM-DD |
| Last updated | YYYY-MM-DD |

## 1. Purpose

This SOP documents the current-state process for monitoring the quality of customer records.

The purpose is to understand how customer record quality issues are identified, checked, prioritised and prepared for correction or escalation.

This SOP should be validated with the officer who performs the work before it is treated as confirmed current practice.

## 2. Scope

## In scope

- checking customer records for quality issues
- identifying incomplete, inaccurate, outdated, duplicated or inconsistent data
- reviewing data quality reports, queues or manual lists if used
- identifying records requiring cleansing or correction
- recording issues requiring follow-up
- escalating data quality issues where required

## Out of scope

- organisation-wide customer experience measurement
- customer service KPI reporting
- complaints or feedback reporting
- formal data governance framework design
- automated data quality monitoring design
- system configuration changes

## 3. Trigger

This process may start when:

| Trigger | Description | Status |
|---|---|---|
| Scheduled data quality review | Customer records are reviewed periodically. | To validate |
| Assigned data quality task | Officer is assigned a set of records to check. | To validate |
| Data quality report or query | A report, query or dashboard identifies possible issues. | To validate |
| Staff request | A staff member identifies a record quality issue. | To validate |
| Duplicate review activity | Record quality issues are identified while checking duplicates. | To validate |
| Manual discovery | Officer notices an issue while completing other work. | To validate |

## 4. Inputs required

| Input | Required? | Source | Notes |
|---|---|---|---|
| Customer record list | To validate | CRM / Salesforce / Pathway / tracker | Records to review. |
| Data quality criteria | To validate | Work instruction / officer knowledge / data standard | Confirm whether documented. |
| System report, query or queue | To validate | CRM / reporting tool / manual list | Confirm actual use. |
| Customer identifiers | To validate | CRM / related systems | Used to assess record quality. |
| Progress tracker | To validate | Spreadsheet / CRM / other tool | Used to record issues or progress. |

## 5. Current process

Draft process to validate:

1. Identify the set of customer records to be reviewed.
2. Open the relevant system, report, query, queue or tracker.
3. Review customer records against current data quality criteria.
4. Check for issues such as:
   - duplicate records
   - missing required fields
   - outdated information
   - inconsistent information
   - unclear customer identity
   - incorrect formatting
   - unreliable or conflicting details
5. Classify each issue by type and level of concern.
6. Decide whether the issue can be corrected, requires further review or needs escalation.
7. Record the issue and current status using the current tracking method.
8. Move the record into the appropriate next process, such as cleansing, correction, de-duplication or escalation.

## 6. Decision points

| Decision | How the decision is made today | Source of rule | Status |
|---|---|---|---|
| Does this record have a quality issue? | Review customer fields against expected criteria. | To validate | Draft |
| What type of data quality issue is this? | Classify as duplicate, missing, outdated, inconsistent or unclear. | To validate | Draft |
| Is the issue significant enough to action? | Assess impact, risk or priority. | To validate | Draft |
| Can the issue be corrected by the officer? | Check access, authority and available evidence. | To validate | Draft |
| Does the issue require escalation? | Escalate unclear, sensitive or system-constrained cases. | To validate | Draft |
| How should the issue be recorded? | Use current tracker, note, queue or system status. | To validate | Draft |

## 7. Systems and tools

| System or tool | Used for | Notes |
|---|---|---|
| Salesforce | Reviewing customer records and data fields. | Confirm actual use. |
| Pathway | Checking related customer or service information. | Confirm actual use. |
| Data quality report or query | Identifying records that may require review. | Confirm if used. |
| Spreadsheet or tracker | Tracking reviewed records, issues and progress. | Confirm if used. |
| Work instruction | Guiding data quality criteria. | Confirm existence and location. |
| Email or Teams | Clarifying or escalating issues. | Confirm actual pathway. |

## 8. Exceptions

| Exception | What happens today | Risk or impact | Status |
|---|---|---|---|
| No clear data quality criteria exists. | To validate. | Inconsistent classification. | Open |
| Record appears poor quality but cannot be corrected. | To validate. | Issue remains unresolved. | Open |
| Information conflicts across systems. | To validate. | Officer may not know which source to trust. | Open |
| Report or query returns false positives. | To validate. | Manual review effort increases. | Open |
| System does not show enough information. | To validate. | Additional checking or escalation required. | Open |
| Issue appears to be caused upstream. | To validate. | Root cause may continue creating data issues. | Open |

## 9. Controls

| Control | Purpose | Status |
|---|---|---|
| Data quality criteria | Defines what counts as a quality issue. | To validate |
| Field review | Checks completeness, accuracy and consistency. | To validate |
| Duplicate check | Identifies uniqueness issues. | To validate |
| Source comparison | Checks conflicting or unclear information. | To validate |
| Issue classification | Groups issues for correction or escalation. | To validate |
| Progress tracking | Maintains visibility of reviewed and unresolved records. | To validate |
| Escalation threshold | Ensures risky or unclear cases are not handled informally. | To validate |

## 10. Handoffs

| From | To | What is handed over | Method | Status |
|---|---|---|---|---|
| Customer Data and Systems Support | Customer Data and Systems Support | Record requiring cleansing, correction or de-duplication. | Internal workflow / tracker to validate | Open |
| Customer Data and Systems Support | Manager or system owner | Unclear or high-risk data quality issue. | To validate | Open |
| Staff member or team | Customer Data and Systems Support | Reported customer record quality issue. | To validate | Open |

## 11. Pain points and risks

| Pain point or risk | Impact | Status |
|---|---|---|
| Quality criteria may be informal or undocumented. | Inconsistent review and reliance on individual knowledge. | To validate |
| Data quality monitoring may depend on manual checks. | Staff effort and scalability limitation. | To validate |
| Reports or queries may not identify all issues. | Some poor-quality records may remain undetected. | To validate |
| False positives may increase workload. | Manual review effort. | To validate |
| Unresolved issues may not be visible. | Continuity and governance risk. | To validate |
| Upstream causes may not be addressed. | Repeated data quality issues. | To validate |

## 12. Omnichannel implications

Monitoring customer record quality helps identify whether customer data is reliable enough to support future omnichannel service delivery.

Current-state observations may inform future requirements such as:

- critical customer data fields
- data quality dashboards
- identity confidence indicators
- incomplete record alerts
- duplicate risk indicators
- unresolved issue queues
- upstream intake validation
- data quality ownership and escalation rules

## 13. Open questions

- Is customer record quality monitored regularly or only through specific tasks?
- What records are reviewed?
- What criteria define a quality issue?
- Are data quality criteria documented?
- What tools, reports or queries are used?
- How are issues classified?
- How are unresolved issues tracked?
- Who decides which issues are prioritised?
- Which issues can the officer correct?
- Which issues require escalation?
- What data quality issues occur most often?
- What upstream sources create recurring issues?

## 14. Validation notes

| Date | Validated with | Changes made | Open issues |
|---|---|---|---|
| YYYY-MM-DD |  |  |  |
