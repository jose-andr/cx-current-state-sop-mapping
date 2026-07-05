# Automation Candidates

## Purpose

This file captures automation candidates emerging from current-state SOP mapping across:

- Customer Data and Systems Support
- Customer Focus Information Support

The purpose is to identify where automation, workflow support, structured rules or system prompts may reduce manual effort, improve consistency or strengthen future omnichannel readiness.

This file does not recommend automation before the current state is validated.

It identifies candidate areas for later assessment.

## Current status

Status: Draft discovery placeholder.

Automation candidates should be validated after SOP walkthroughs confirm actual work, current controls, risks and human judgement points.

## Important boundary

Automation should not be used to bypass human judgement, ownership or governance.

Before any automation candidate is progressed, confirm:

- the process is real current-state work
- the rule or trigger is understood
- the data or content source is trustworthy
- ownership is clear
- approval requirements are known
- human review thresholds are defined
- risk of incorrect automation is acceptable
- manual fallback exists

## Candidate inventory

| Candidate ID | Candidate | Related function | Current manual work | Potential automation type | Status |
|---|---|---|---|---|---|
| AC-001 | Duplicate customer record detection support | Customer Data and Systems Support | Manually reviewing possible duplicate records. | Matching rules, confidence scoring, exception queue. | Candidate |
| AC-002 | Customer data quality issue flagging | Customer Data and Systems Support | Manually identifying incomplete, incorrect or inconsistent customer data. | Validation rules, data quality alerts, exception reports. | Candidate |
| AC-003 | Data cleansing progress tracking | Customer Data and Systems Support | Manually recording cleansing progress and follow-up actions. | Workflow states, task queues, dashboard or status tracker. | Candidate |
| AC-004 | Repeated data issue pattern detection | Customer Data and Systems Support | Manually noticing repeated causes of data quality issues. | Pattern reporting, error category tagging, trend prompts. | Candidate |
| AC-005 | Service content review reminders | Customer Focus Information Support | Manually remembering or checking content that needs review. | Review dates, owner reminders, expiry alerts. | Candidate |
| AC-006 | Duplicate service information detection | Customer Focus Information Support | Manually checking whether guidance appears across multiple tools. | Similarity detection, duplicate content prompts, source-of-truth tagging. | Candidate |
| AC-007 | Urgent update workflow support | Customer Focus Information Support | Manually coordinating urgent updates, approvals and staff communication. | Structured request form, approval status, distribution checklist. | Candidate |
| AC-008 | Message on hold expiry alerts | Customer Focus Information Support | Manually remembering to retire outdated phone messages. | Expiry dates, automated reminders, active-message register. | Candidate |
| AC-009 | Editor support request triage | Customer Focus Information Support | Manually classifying editor requests. | Request category form, routing rules, status tracking. | Candidate |
| AC-010 | CRM support request classification | Both | Manually distinguishing data, knowledge, access, system and technical issues. | Intake form, issue taxonomy, routing rules. | Candidate |
| AC-011 | Knowledge gap detection from repeated questions | Both | Manually noticing recurring staff questions or escalations. | Tagging, trend capture, feedback prompts. | Candidate |
| AC-012 | Cross-tool consistency checking | Both | Manually checking whether updates affect other systems or tools. | Dependency map, update impact prompts, consistency checklist. | Candidate |

## Assessment criteria

Use these criteria before prioritising any automation candidate.

| Criterion | Assessment question |
|---|---|
| Current-state validity | Is the activity confirmed as actual current practice? |
| Frequency | How often does the activity occur? |
| Effort | How much manual effort does the activity require? |
| Risk | What could go wrong if automation is wrong? |
| Rule clarity | Are the decision rules clear enough to support automation? |
| Source quality | Are the data or knowledge sources reliable? |
| Ownership | Who owns the information, process or outcome? |
| Approval needs | Does a human need to approve before action is taken? |
| Exception rate | How often do cases require judgement or escalation? |
| Reversibility | Can an incorrect automated action be corrected safely? |
| Auditability | Is an evidence trail required? |
| Staff experience | Would automation reduce friction or create confusion? |
| Customer impact | Would automation improve consistency, timeliness or accuracy? |
| Omnichannel value | Would automation support reusable data or knowledge foundations? |

## Candidate detail template

Use this template to expand each candidate.

## Automation candidate: [candidate name]

| Attribute | Details |
|---|---|
| Candidate ID |  |
| Related function |  |
| Related SOPs |  |
| Current manual activity |  |
| Trigger |  |
| Possible automation |  |
| Required data or content source |  |
| Required rule or logic |  |
| Human review threshold |  |
| Approval requirement |  |
| Exception pathway |  |
| Risk if automated incorrectly |  |
| Manual fallback |  |
| Evidence needed |  |
| Business case signal |  |
| Status | Candidate / validated / rejected / deferred |

## Automation patterns

## 1. Detection before action

Some automation should only detect or flag issues.

Examples:

- possible duplicate records
- incomplete customer data
- duplicated service information
- content due for review
- urgent message nearing expiry

Design principle:

Automation may identify a candidate issue, but a person may still need to confirm and act.

## 2. Workflow support before decision automation

Some opportunities are not about replacing judgement.

They are about making work visible.

Examples:

- approval status
- review due dates
- escalation state
- pending owner response
- completed update confirmation
- unresolved issue queue

Design principle:

Automate visibility, reminders and routing before automating decisions.

## 3. Structured intake before advanced automation

Many current-state issues may first need better classification.

Examples:

- CRM support issue type
- data quality issue type
- content update request type
- urgent update type
- editor support request type

Design principle:

Good automation depends on clean intake categories and consistent metadata.

## 4. Reuse before channel expansion

Future omnichannel channels should not reuse weak, outdated or unowned information.

Examples:

- chatbot answer reuse
- web content reuse
- staff script reuse
- CRM prompt reuse
- telephone message reuse

Design principle:

Automate reuse only after ownership, source-of-truth and lifecycle rules are clear.

## 5. Human judgement thresholds

Some decisions should remain human-led because they require context, risk assessment or accountability.

Examples:

- whether two customer records are definitely the same person
- whether conflicting service information can be resolved
- whether urgent guidance can be issued without full approval
- whether sensitive customer-facing information should be published
- whether an exception should be escalated

Design principle:

Define confidence thresholds, exception categories and approval gates.

## Business case signals

| Signal | Why it matters |
|---|---|
| Repeated manual checks indicate automation potential. | Candidate workflows may reduce effort and improve consistency. |
| Manual trackers indicate missing workflow visibility. | Future tools could provide task state, ownership and audit trail. |
| Recurring issue types indicate classification value. | Better intake taxonomy can improve routing and reporting. |
| Review and expiry tasks are time-sensitive but predictable. | Reminders and lifecycle controls are low-risk automation candidates. |
| Duplicate detection requires judgement but can be assisted. | Automation can support triage without replacing final decision-making. |
| Cross-tool consistency depends on memory. | System prompts can reduce missed updates and conflicting information. |
| Omnichannel reuse requires governed inputs. | Automation must be built on trusted data and service knowledge foundations. |

## Exclusions for now

Do not treat these as automation candidates unless validated later:

- broad CX measurement and analysis
- monthly Customer Service Indicator reporting
- customer feedback and complaints reporting
- organisation-wide performance analysis
- automated decision-making about sensitive customer data
- automatic publication of unapproved service information
- automatic merging of customer records without human review

## Review notes

| Date | Update | Updated by |
|---|---|
| YYYY-MM-DD | Initial draft placeholder created. |  |
