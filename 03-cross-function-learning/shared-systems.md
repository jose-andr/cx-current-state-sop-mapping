# Shared Systems

## Purpose

This file captures systems, tools and information environments that may be relevant across both current-state functions:

- Customer Data and Systems Support
- Customer Focus Information Support

The purpose is to identify shared dependencies, duplication, governance gaps and future architecture signals without merging the two functions prematurely.

## Current status

Status: Draft discovery placeholder.

System usage should be validated through SOP walkthroughs and officer interviews.

## Shared systems inventory

| System or tool | Customer Data and Systems Support use | Customer Focus Information Support use | Shared dependency | Status |
|---|---|---|---|---|
| CRM | Customer record review, duplicate identification, data correction and data maintenance support. | CRM user support, service information context and staff guidance support. | Shared customer service platform dependency. | To validate |
| Salesforce | Customer data and customer record work where relevant. | CRM support and possible service information context where relevant. | Shared CRM environment or dependency. | To validate |
| Pathway | Customer record or service module dependency where relevant. | Customer service module or CRM support dependency where relevant. | Shared legacy or operational system dependency. | To validate |
| Service Directory | May inform customer service context when data issues relate to service handling. | Core service information and first contact resolution content. | Shared staff guidance dependency. | To validate |
| Customer Focus Portal | May support reference information or staff guidance. | Customer service information, updates and staff support. | Shared knowledge environment. | To validate |
| CoMWeb / intranet | May provide internal reference information. | Internal staff information and related customer service content. | Shared internal information environment. | To validate |
| Email | Intake, clarification, approvals, escalation and follow-up. | Intake, approvals, urgent updates, editor support and follow-up. | Shared informal workflow channel. | To validate |
| Teams | Quick clarification, informal escalation and coordination. | Urgent coordination, editor support and branch updates. | Shared informal coordination channel. | To validate |
| Trackers / spreadsheets | Progress tracking, cleansing work, issue tracking or work queues. | Content updates, urgent messages, editor issues or tool changes. | Shared manual visibility and continuity mechanism. | To validate |
| Reports or exports | Data quality review, duplicate identification or cleansing queues. | Possible content issue tracking or staff support patterns if used. | Shared evidence and monitoring dependency. | To validate |

## System relationship themes

## 1. CRM as a shared operating environment

The CRM may be used differently by each function.

Customer Data and Systems Support focuses on customer record integrity and data quality.

Customer Focus Information Support may interact with CRM from a staff support, user guidance or service information perspective.

Future implication:

- distinguish data quality support from user guidance support
- define CRM issue categories
- define escalation pathways for access, defect, data and guidance issues
- document where CRM is system of record and where it is only a working interface

## 2. Service knowledge systems as shared staff infrastructure

Service Directory, Customer Focus Portal, CoMWeb and related tools may support customer-facing staff.

Future implication:

- define which tool is authoritative for which information type
- define which tools are staff-facing, customer-facing or internal-only
- identify duplicated information across tools
- define content ownership and review cycles
- identify content suitable for reuse across channels

## 3. Email and Teams as hidden workflow systems

Email and Teams may be performing workflow functions that are not formally designed into the system architecture.

They may support:

- request intake
- clarification
- approval
- escalation
- urgent updates
- completion confirmation
- informal knowledge transfer

Future implication:

- identify which informal workflows should remain lightweight
- identify which workflows need tracking, status or governance
- define when a request should become a ticket, task or controlled update
- reduce dependency on inbox history and personal relationships

## 4. Trackers and spreadsheets as continuity tools

Manual trackers may provide visibility where systems do not.

They may record:

- data cleansing progress
- duplicate record work
- content updates
- unresolved issues
- urgent messages
- review dates
- follow-up actions

Future implication:

- identify which manual trackers are essential controls
- identify duplicated tracking effort
- determine where workflow tooling could reduce manual coordination
- preserve evidence and auditability when redesigning tools

## 5. Reports and exports as work generators

Reports, exports or lists may trigger current-state work.

For Customer Data and Systems Support, this may include duplicate detection or data quality monitoring.

For Customer Focus Information Support, this may include content issues, staff feedback or update lists where confirmed.

Future implication:

- distinguish formal reporting from operational work queues
- avoid assuming broad CX analytics unless validated as actual practice
- capture what evidence currently drives corrective work
- identify where proactive monitoring could improve quality

## Shared system dependency map

Use this table during discovery.

| Dependency ID | System or tool | Dependency description | Function affected | Risk if unavailable or unreliable | Current workaround | Status |
|---|---|---|---|---|---|---|
| SD-001 | CRM | Customer records and CRM support requests depend on reliable CRM access and information. | Both | Data and support work may be delayed. | To validate | Open |
| SD-002 | Service Directory | Staff guidance depends on accurate and current service information. | Customer Focus Information Support | Staff may provide inconsistent advice. | To validate | Open |
| SD-003 | Email | Many requests, approvals or escalations may arrive through email. | Both | Work may become hard to track or hand over. | To validate | Open |
| SD-004 | Teams | Quick coordination may happen outside formal tracking. | Both | Decisions may not be recorded. | To validate | Open |
| SD-005 | Trackers / spreadsheets | Visibility may depend on manual records. | Both | Work status may be unclear if tracker is incomplete. | To validate | Open |

## System classification prompts

Use these prompts to classify each system.

- Is this system a source of truth, a publishing location, a workflow tool or a reference tool?
- Who owns the system?
- Who owns the information inside the system?
- Who can update the system?
- Who approves changes?
- What work starts from this system?
- What work ends in this system?
- What information is duplicated from or to this system?
- What happens when this system is unavailable?
- What information should not be stored in this system?
- What data or content quality issue appears most often?
- What other systems depend on this system being correct?

## Future architecture signals

| Signal | Why it matters |
|---|---|
| Same system supports different types of work. | Future operating model needs clearer support categories and responsibilities. |
| Information may be duplicated across tools. | Future architecture needs source-of-truth and reuse rules. |
| Email and Teams may carry workflow decisions. | Future workflows may need better tracking, status and auditability. |
| Manual trackers may compensate for system gaps. | Future tooling may need work queues, lifecycle states or automated reminders. |
| CRM issues may include data, guidance, access and technical problems. | Future support model should classify and route CRM issues more clearly. |
| Service information quality affects staff confidence. | Future knowledge architecture should be treated as core service infrastructure. |

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
