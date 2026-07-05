# Systems and Tools

## Function

Customer Data and Systems Support

## Purpose

This file captures the systems, tools, trackers and information sources used by the Customer Data and Systems Support function.

The goal is to understand where work happens, where data is checked or changed, and where system dependencies create risk, effort or future omnichannel implications.

## Current status

Status: Draft discovery placeholder.

Systems and tools should be validated with the officer who performs the work.

## System and tool inventory

| System or tool | Used for | Current owner | User role or access | Status | Notes |
|---|---|---|---|---|---|
| Salesforce | Customer record review, cleansing, correction or de-duplication. | To validate | To validate | To validate | Confirm actual use. |
| Pathway | Customer service module or related customer data reference. | To validate | To validate | To validate | Confirm actual use. |
| Master Data Management process or tool | Data quality and customer record management. | To validate | To validate | To validate | Confirm whether formal MDM tooling exists in practice. |
| Spreadsheets or trackers | Tracking cleansing progress, unresolved items or manual work. | To validate | To validate | To validate | Capture if used. |
| Shared mailbox | Receiving requests or updates. | To validate | To validate | To validate | Capture if used. |
| CRM queue or task list | Receiving or managing work. | To validate | To validate | To validate | Capture if used. |
| Work instructions | Guiding data correction or duplicate management. | To validate | To validate | To validate | Capture location and currency. |
| Data quality reports or dashboards | Identifying records requiring review. | To validate | To validate | To validate | Do not assume active use. |
| Team communication channel | Clarifying issues or escalating questions. | To validate | To validate | To validate | Capture Teams, email or other channels if used. |

## System dependency map

Use this table to capture how each system supports the work.

| Work activity | System or tool used | Information checked | Information changed | Output |
|---|---|---|---|---|
| Identify duplicate records | To validate | To validate | To validate | To validate |
| Review duplicate candidates | To validate | To validate | To validate | To validate |
| Cleanse customer records | To validate | To validate | To validate | To validate |
| Manually de-duplicate records | To validate | To validate | To validate | To validate |
| Correct data quality issues | To validate | To validate | To validate | To validate |
| Track progress | To validate | To validate | To validate | To validate |
| Escalate data or system issue | To validate | To validate | To validate | To validate |

## Access and permissions

Use this section to capture system permissions and constraints.

| System or tool | What the officer can do | What the officer cannot do | Escalation path |
|---|---|---|---|
| Salesforce | To validate | To validate | To validate |
| Pathway | To validate | To validate | To validate |
| MDM tool or process | To validate | To validate | To validate |
| Spreadsheets or trackers | To validate | To validate | To validate |

## Data movement

Use this section to capture where data is copied, moved, exported or re-entered.

| From | To | Data moved | Method | Risk or issue |
|---|---|---|---|---|
| To validate | To validate | To validate | Manual / automated / export / copy-paste | To validate |

## Known or suspected pain points

| Pain point | Affected system or tool | Impact | Status |
|---|---|---|---|
| Duplicate records may require manual review. | Salesforce / CRM | Staff effort, data quality risk, customer context risk. | To validate |
| Data correction rules may not be fully documented. | CRM / work instructions | Inconsistent decisions or escalation. | To validate |
| Progress tracking may occur outside the system of record. | Spreadsheet or tracker | Visibility and continuity risk. | To validate |
| System limitations may create manual workarounds. | CRM / related tools | Rework and operational dependency. | To validate |

## Omnichannel implications

Capture implications for future connected service delivery.

| Current-state observation | Omnichannel implication | Type |
|---|---|---|
| Customer records may contain duplicates. | Customer identity and context may not carry reliably across channels. | Data quality |
| Customer data correction may be manual. | Automation and self-service may depend on stronger data quality controls. | Automation readiness |
| Work may rely on system-specific knowledge. | Future support model may need clearer ownership and documented system rules. | Governance |
| Progress tracking may sit outside core systems. | Future workflow may need clearer visibility of status and completed actions. | Workflow |

## Discovery questions

- Which systems are used every day?
- Which systems are used occasionally?
- Which tools are official sources of truth?
- Which tools are informal or local workarounds?
- What information is checked before a record is changed?
- What information is changed directly?
- What information cannot be changed by the officer?
- What work requires exporting or copying information?
- What system permissions limit the work?
- What system issues require escalation?
- What work instructions are used?
- Where are work instructions stored?
- How does the officer know which system record is correct?
- Where is completed work recorded?
- Which system dependencies would affect future omnichannel service delivery?

## Review notes

| Date | Update | Updated by |
|---|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
