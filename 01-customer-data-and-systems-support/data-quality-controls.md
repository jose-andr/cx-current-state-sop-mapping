# Data Quality Controls

## Function

Customer Data and Systems Support

## Purpose

This file captures the checks, safeguards and rules used to maintain customer data quality.

Data quality controls are important because customer data affects service consistency, customer context, privacy, reporting, workflow and future omnichannel capability.

## Current status

Status: Draft discovery placeholder.

Controls should be validated with the officer who performs the work.

## Data quality dimensions

Use these dimensions when mapping customer record quality.

| Dimension | Meaning | Example question |
|---|---|---|
| Accuracy | Data correctly reflects the customer, account or entity. | Is this information correct? |
| Completeness | Required fields or details are present. | Is anything missing? |
| Currency | Data is up to date. | Is this still the current address, phone number or account detail? |
| Uniqueness | One customer, account or entity is represented once. | Are there duplicate records? |
| Consistency | Data is represented in the same way across systems or records. | Do related systems show the same information? |
| Validity | Data follows required format, rule or standard. | Is the field completed in the correct format? |
| Traceability | It is clear what was changed, why, when and by whom. | Can we see the correction history? |

## Control inventory

| Control ID | Control | Related activity | Purpose | Status | Notes |
|---|---|---|---|---|---|
| C-001 | Duplicate search or query | Identify duplicate customer records | Find records that may represent the same customer or entity. | To validate | Confirm search criteria and tool. |
| C-002 | Record comparison | Review duplicate candidates | Compare fields before deciding whether records are duplicates. | To validate | Confirm fields compared. |
| C-003 | Primary record selection rule | Manual de-duplication | Decide which record should be retained. | To validate | Confirm whether documented. |
| C-004 | Required information check | Data correction | Confirm enough information exists before correcting a record. | To validate | Confirm required fields or evidence. |
| C-005 | Privacy or sensitivity check | Data correction and de-duplication | Prevent inappropriate changes or linking of records. | To validate | Confirm privacy guidance. |
| C-006 | Permission or access check | CRM data maintenance | Confirm officer has authority and system access to complete action. | To validate | Confirm access limits. |
| C-007 | Escalation threshold | Exception handling | Identify when a case should be escalated. | To validate | Confirm escalation rules. |
| C-008 | Progress tracking | Cleansing work | Track completed, pending or unresolved work. | To validate | Confirm tracker or system. |
| C-009 | Completion check | Record progress | Confirm work has been completed and recorded. | To validate | Confirm completion criteria. |

## Control detail template

Use this structure to expand each control.

## Control: [control name]

| Attribute | Details |
|---|---|
| Control ID |  |
| Related SOP |  |
| Control purpose |  |
| When it occurs |  |
| Who performs it |  |
| Inputs required |  |
| Rule or standard |  |
| Evidence checked |  |
| Output |  |
| Where recorded |  |
| Failure mode |  |
| Escalation path |  |
| Current reliability | High / medium / low |
| Notes |  |

## Possible control failures

| Failure | Related control | Potential impact |
|---|---|---|
| Duplicate not identified | Duplicate search or query | Customer context remains fragmented. |
| Two different customers merged | Record comparison / primary record selection | Privacy, data integrity and customer impact risk. |
| Wrong record retained | Primary record selection rule | Loss of useful history or incorrect customer context. |
| Data changed without enough evidence | Required information check | Inaccurate or unreliable customer record. |
| Sensitive record changed incorrectly | Privacy or sensitivity check | Compliance and trust risk. |
| Correction not recorded | Progress tracking / completion check | Poor traceability and continuity. |
| Unclear case not escalated | Escalation threshold | Inconsistent or risky decision-making. |

## Data quality control questions

Ask these during discovery:

- What makes a customer record high quality?
- What fields matter most?
- Which fields are most often wrong?
- Which fields are most often missing?
- Which fields are most important for identifying a customer?
- Which fields are most important for service delivery?
- How are duplicate records found?
- How do you confirm records are duplicates?
- How do you decide which record to keep?
- What information must not be changed without approval?
- What corrections can you make independently?
- What corrections require escalation?
- What rules are written down?
- What rules are known through experience?
- How is completed work recorded?
- How do you check whether a correction worked?
- How do you know the data is now reliable?

## Omnichannel implications

| Data quality control | Omnichannel implication |
|---|---|
| Duplicate identification | Supports reliable customer recognition across channels. |
| Record comparison | Reduces risk of fragmented or incorrect customer context. |
| Primary record selection | Helps create a clearer source of truth for customer identity. |
| Required information check | Supports better intake design and mandatory field rules. |
| Privacy or sensitivity check | Defines where human review is needed before automation. |
| Progress tracking | Supports visibility of completed and unresolved data work. |
| Escalation threshold | Helps define future exception routing and governance. |

## Review notes

| Date | Update | Updated by |
|---|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
