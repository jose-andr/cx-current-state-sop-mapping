# GitHub Implementation Checklist

## Purpose

This checklist guides the setup of a GitHub repository for mapping the current-state SOPs of two CX functions:

1. Customer Data and Systems Support
2. Customer Focus Information Support

The purpose of the repository is to document how work is actually performed today, identify pain points and exceptions, and create a structured evidence base for future omnichannel service design, information reuse and operating model development.

## Progress update

Last updated: YYYY-MM-DD

Today’s progress completed:

- Project control files drafted
- Customer Data and Systems Support function folder drafted
- Customer Data and Systems Support SOPs 001 to 008 drafted
- Customer Focus Information Support function folder drafted
- Customer Focus Information Support SOPs 001 to 008 drafted
- Cross-function learning files drafted
- Core reusable templates drafted
- First decision record drafted
- Work stopped at `05-decisions/ADR-001-map-actual-practice-not-aspirational-pd.md`

---

## Phase 1: Repository setup

### 1. Create repository

* [ ] Create a new repository called `cx-current-state-sop-mapping`

* [ ] Set repository visibility according to current organisational requirements

* [ ] Add a short repository description:

  `Current-state SOP mapping for CX data, systems and information support functions.`

* [ ] Do not upload customer data, personal information, credentials, restricted operational material or sensitive examples

### 2. Add initial folder structure

* [x] Create `00-project-control/`
* [x] Create `01-customer-data-and-systems-support/`
* [x] Create `02-customer-focus-information-support/`
* [x] Create `03-cross-function-learning/`
* [x] Create `04-templates/`
* [x] Create `05-decisions/`

### 3. Add starter files

* [x] Add `README.md`
* [x] Add `00-project-control/purpose-and-scope.md`
* [x] Add `00-project-control/working-principles.md`
* [x] Add `00-project-control/co-design-session-guide.md`
* [x] Add `00-project-control/role-intent-vs-actual-practice.md`
* [x] Add `00-project-control/assumptions-log.md`
* [x] Add `00-project-control/glossary.md`

---

## Phase 2: Establish mapping principles

### 4. Confirm current-state mapping rule

* [x] Document that the repository maps actual current practice, not aspirational role descriptions
* [x] Confirm that position descriptions are used as reference material only
* [x] Capture any role responsibilities that exist in a PD but are not performed in practice as role-gap notes
* [x] Avoid creating SOPs for work that is not currently performed

### 5. Add decision records

Create the following files in `05-decisions/`:

* [x] `ADR-001-map-actual-practice-not-aspirational-pd.md`
* [ ] `ADR-002-keep-functions-separated-during-current-state-discovery.md`
* [ ] `ADR-003-use-github-for-sop-discovery.md`
* [ ] `ADR-004-design-for-future-enterprise-migration.md`

### 6. Confirm separation of functions

* [x] Keep Customer Data and Systems Support separate from Customer Focus Information Support
* [x] Do not merge workflows during current-state discovery
* [x] Capture overlaps only in `03-cross-function-learning/`
* [x] Review shared patterns after both functions have been mapped

---

## Phase 3: Create function folders

### 7. Customer Data and Systems Support

Create the following files in `01-customer-data-and-systems-support/`:

* [x] `README.md`
* [x] `role-context.md`
* [x] `actual-practice-summary.md`
* [x] `pd-intent-vs-current-reality.md`
* [x] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [x] `work-types.md`
* [x] `systems-and-tools.md`
* [x] `decision-points.md`
* [x] `exception-pathways.md`
* [x] `data-quality-controls.md`
* [x] `pain-points-and-risks.md`
* [x] `omnichannel-implications.md`

Create the SOP folder:

* [x] `01-customer-data-and-systems-support/sops/`

Add starter SOP files:

* [x] `CDSS-SOP-001-identify-duplicate-customer-records.md`
* [x] `CDSS-SOP-002-cleanse-and-simplify-customer-records.md`
* [x] `CDSS-SOP-003-manually-deduplicate-customer-records.md`
* [x] `CDSS-SOP-004-monitor-customer-record-quality.md`
* [x] `CDSS-SOP-005-correct-customer-data-quality-issues.md`
* [x] `CDSS-SOP-006-record-progress-of-data-cleansing-work.md`
* [x] `CDSS-SOP-007-escalate-data-quality-or-system-issues.md`
* [x] `CDSS-SOP-008-support-basic-crm-data-maintenance-requests.md`

### 8. Customer Focus Information Support

Create the following files in `02-customer-focus-information-support/`:

* [x] `README.md`
* [x] `role-context.md`
* [x] `actual-practice-summary.md`
* [x] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [x] `knowledge-and-work-types.md`
* [x] `systems-and-tools.md`
* [x] `decision-points.md`
* [x] `exception-pathways.md`
* [x] `content-quality-controls.md`
* [x] `pain-points-and-risks.md`
* [x] `omnichannel-implications.md`

Create the SOP folder:

* [x] `02-customer-focus-information-support/sops/`

Add starter SOP files:

* [x] `CFIS-SOP-001-update-service-directory-content.md`
* [x] `CFIS-SOP-002-maintain-customer-service-tools.md`
* [x] `CFIS-SOP-003-support-crm-user-issues-and-requests.md`
* [x] `CFIS-SOP-004-maintain-telephone-messages-on-hold.md`
* [x] `CFIS-SOP-005-coordinate-hot-topic-customer-responses.md`
* [x] `CFIS-SOP-006-communicate-urgent-updates-to-branch-staff.md`
* [x] `CFIS-SOP-007-support-service-directory-editors.md`
* [x] `CFIS-SOP-008-improve-first-contact-resolution-content.md`

---

## Phase 4: Add reusable templates

Create the following files in `04-templates/`:

* [x] `sop-discovery-template.md`
* [x] `current-state-sop-template.md`
* [x] `pain-point-register-template.md`
* [x] `risk-register-template.md`
* [x] `assumptions-register-template.md`
* [x] `decision-log-template.md`
* [x] `evidence-register-template.md`
* [x] `stakeholder-interview-guide-template.md`
* [x] `system-inventory-template.md`
* [x] `source-of-truth-assessment-template.md`
* [x] `workflow-and-lifecycle-template.md`
* [x] `business-case-evidence-template.md`
* [x] `validation-checklist-template.md`

Deferred or replaced from the original starter list:

* [ ] `process-observation-template.md`
* [ ] `decision-table-template.md`
* [ ] `exception-log-template.md`
* [ ] `omnichannel-implication-template.md`

Note:

The original checklist included `interview-guide-template.md`, `pain-point-log-template.md` and other early template names. Today’s work used more explicit names aligned to the repo structure, including `stakeholder-interview-guide-template.md` and `pain-point-register-template.md`.

---

## Phase 5: Co-design preparation

### 9. Prepare officer mapping sessions

* [ ] Schedule one mapping session with the Customer Data and Systems Support officer
* [ ] Schedule one mapping session with the Customer Focus Information Support officer
* [x] Use the same discovery structure for both sessions
* [x] Begin each session by asking what work actually lands on the officer’s desk in a normal week
* [x] Do not start with the PD accountabilities
* [x] Use the PD only as a reference check after actual work has been mapped

### 10. Use a consistent mapping structure

For each function, capture:

* [x] Work types
* [x] Triggers
* [x] Inputs
* [x] Systems and tools
* [x] Process steps
* [x] Decision points
* [x] Handoffs
* [x] Exceptions
* [x] Workarounds
* [x] Controls
* [x] Pain points
* [x] Risks
* [x] Improvement opportunities
* [x] Omnichannel implications

---

## Phase 6: Map Customer Data and Systems Support

### 11. Confirm actual work types

* [x] Identify recurring weekly work
* [x] Identify ad hoc requests
* [x] Identify system or data maintenance activities
* [x] Identify customer record quality activities
* [x] Identify work that exists in the PD but is not performed in practice
* [x] Add non-performed PD responsibilities to `pd-intent-vs-current-reality.md`

### 12. Draft first SOPs

Prioritise SOPs that are real, recurring and operationally important:

* [x] Identify duplicate customer records
* [x] Cleanse and simplify customer records
* [x] Manually de-duplicate customer records
* [x] Monitor customer record quality
* [x] Correct customer data quality issues
* [x] Record progress of data cleansing work
* [x] Escalate data quality or system issues
* [x] Support basic CRM data maintenance requests

### 13. Capture future signals

* [x] Note what customer data issues affect channel continuity
* [x] Note what customer identity or account context issues create rework
* [x] Note what data quality issues could block automation
* [x] Note what system constraints affect staff or customers

---

## Phase 7: Map Customer Focus Information Support

### 14. Confirm actual work types

* [x] Identify recurring content and information maintenance work
* [x] Identify urgent information update work
* [x] Identify CRM or user support work
* [x] Identify Service Directory editor support work
* [x] Identify customer service tool update work
* [x] Identify work that is informal, undocumented or dependent on individual knowledge

### 15. Draft first SOPs

Prioritise SOPs that are real, recurring and operationally important:

* [x] Update Service Directory content
* [x] Maintain customer service tools
* [x] Support CRM user issues and requests
* [x] Maintain telephone messages on hold
* [x] Coordinate hot topic customer responses
* [x] Communicate urgent updates to branch staff
* [x] Support Service Directory editors
* [x] Improve first contact resolution content

### 16. Capture future signals

* [x] Note what information is duplicated across systems
* [x] Note what information lacks clear ownership
* [x] Note what knowledge could be reused across channels
* [x] Note what information quality issues affect first contact resolution
* [x] Note what knowledge gaps could block automation or self-service

---

## Phase 8: Compare without merging

### 17. Populate cross-function learning folder

Create or update:

* [x] `03-cross-function-learning/common-patterns.md`
* [x] `03-cross-function-learning/shared-systems.md`
* [x] `03-cross-function-learning/shared-governance-gaps.md`
* [x] `03-cross-function-learning/shared-data-and-knowledge-dependencies.md`
* [x] `03-cross-function-learning/role-gap-and-capability-signals.md`
* [x] `03-cross-function-learning/automation-candidates.md`
* [x] `03-cross-function-learning/future-operating-model-signals.md`

### 18. Look for patterns

Capture shared patterns across both functions:

* [x] Shared systems
* [x] Shared handoffs
* [x] Shared unclear ownership
* [x] Shared manual workarounds
* [x] Shared quality risks
* [x] Shared dependency on individual knowledge
* [x] Shared automation opportunities
* [x] Shared omnichannel readiness gaps

---

## Phase 9: GitHub working practices

### 19. Use simple version control

* [ ] Use clear commit messages
* [ ] Commit small logical changes
* [ ] Avoid large mixed-purpose commits
* [x] Keep draft files marked as draft
* [x] Use version numbers inside SOP files

Example commit messages:

* `Add initial repo structure`
* `Add current-state mapping principles`
* `Add Customer Data and Systems Support SOP inventory`
* `Draft CFIS Service Directory update SOP`
* `Add role intent vs actual practice note`
* `Draft CDSS current-state SOPs`
* `Draft CFIS current-state SOPs`
* `Add cross-function learning files`
* `Add reusable SOP mapping templates`
* `Add ADR for actual practice mapping rule`

### 20. Use issues for open questions

Create GitHub issues for:

* [ ] Missing process information
* [ ] Unclear ownership
* [ ] Policy or approval questions
* [ ] System constraints
* [ ] Data quality risks
* [ ] Content governance gaps
* [ ] Automation candidates
* [ ] Enterprise migration questions

### 21. Use labels

Suggested labels:

* [ ] `current-state`
* [ ] `sop`
* [ ] `data-quality`
* [ ] `service-knowledge`
* [ ] `systems`
* [ ] `decision-point`
* [ ] `exception`
* [ ] `pain-point`
* [ ] `risk`
* [ ] `omnichannel`
* [ ] `automation-candidate`
* [ ] `role-gap`
* [ ] `enterprise-migration`

---

## Phase 10: Enterprise migration readiness

### 22. Keep the prototype enterprise-safe

* [x] Do not include customer records
* [x] Do not include screenshots with personal information
* [x] Do not include system credentials
* [x] Do not include restricted operational material
* [x] Do not include confidential staff information
* [x] Use fictional or anonymised examples only

### 23. Prepare for future migration

Create `05-decisions/ADR-004-design-for-future-enterprise-migration.md` and capture:

* [ ] Potential enterprise owner
* [ ] Repository access model
* [ ] Review and approval process
* [ ] Information classification requirements
* [ ] Records management considerations
* [ ] Long-term source of truth
* [ ] Integration with CRM, Service Directory, intranet, web, chatbot or reporting platforms

Status:

* [ ] `05-decisions/ADR-004-design-for-future-enterprise-migration.md`

---

## Phase 11: Remaining decision records

Create the remaining decision records:

* [ ] `05-decisions/ADR-002-keep-functions-separated-during-current-state-discovery.md`
* [ ] `05-decisions/ADR-003-use-github-for-sop-discovery.md`
* [ ] `05-decisions/ADR-004-design-for-future-enterprise-migration.md`

Suggested next file:

* [ ] `05-decisions/ADR-002-keep-functions-separated-during-current-state-discovery.md`

---

## Phase 12: Remaining current-state process maps

Create current-state process map files for each function:

* [ ] `01-customer-data-and-systems-support/current-state-process-map.md`
* [ ] `02-customer-focus-information-support/current-state-process-map.md`

These were listed in the original checklist but were not drafted today.

---

## Phase 13: Optional remaining templates

Consider whether the following additional templates are still needed.

Some may be redundant because broader templates have already been created.

* [ ] `04-templates/process-observation-template.md`
* [ ] `04-templates/decision-table-template.md`
* [ ] `04-templates/exception-log-template.md`
* [ ] `04-templates/omnichannel-implication-template.md`

---

## Definition of done for V0.1

The V0.1 repository is complete when:

* [ ] Repository structure is created in GitHub
* [x] README is drafted
* [x] Mapping principles are documented
* [x] Both functions have separate folders drafted
* [x] Each function has a draft SOP inventory
* [x] At least two current-state SOPs are drafted for each function
* [x] Role intent vs actual practice is documented
* [x] Cross-function learning folder is drafted
* [x] Key shared patterns are captured
* [ ] Enterprise migration considerations are documented
* [x] No sensitive customer or operational data is stored in the repository content drafted today

---

## Definition of done for V1

The V1 repository is complete when:

* [ ] Each function has a validated SOP inventory
* [ ] Priority SOPs have been mapped with the officers who perform the work
* [x] Decision points and exceptions are drafted
* [x] Pain points and risks are drafted
* [x] Omnichannel implications are captured
* [x] Role gaps are identified as draft signals
* [x] Automation candidates are listed
* [x] Shared governance gaps are visible
* [x] Future operating model signals are synthesised
* [ ] The repository can support a business case for a more mature CX operating capability after validation and evidence collection

---

## Progress summary by folder

### `00-project-control/`

* [x] `purpose-and-scope.md`
* [x] `working-principles.md`
* [x] `role-intent-vs-actual-practice.md`
* [x] `co-design-session-guide.md`
* [x] `assumptions-log.md`
* [x] `glossary.md`

### `01-customer-data-and-systems-support/`

* [x] `README.md`
* [x] `role-context.md`
* [x] `actual-practice-summary.md`
* [x] `pd-intent-vs-current-reality.md`
* [x] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [x] `work-types.md`
* [x] `systems-and-tools.md`
* [x] `decision-points.md`
* [x] `exception-pathways.md`
* [x] `data-quality-controls.md`
* [x] `pain-points-and-risks.md`
* [x] `omnichannel-implications.md`

### `01-customer-data-and-systems-support/sops/`

* [x] `CDSS-SOP-001-identify-duplicate-customer-records.md`
* [x] `CDSS-SOP-002-cleanse-and-simplify-customer-records.md`
* [x] `CDSS-SOP-003-manually-deduplicate-customer-records.md`
* [x] `CDSS-SOP-004-monitor-customer-record-quality.md`
* [x] `CDSS-SOP-005-correct-customer-data-quality-issues.md`
* [x] `CDSS-SOP-006-record-progress-of-data-cleansing-work.md`
* [x] `CDSS-SOP-007-escalate-data-quality-or-system-issues.md`
* [x] `CDSS-SOP-008-support-basic-crm-data-maintenance-requests.md`

### `02-customer-focus-information-support/`

* [x] `README.md`
* [x] `role-context.md`
* [x] `actual-practice-summary.md`
* [x] `sop-inventory.md`
* [ ] `current-state-process-map.md`
* [x] `knowledge-and-work-types.md`
* [x] `systems-and-tools.md`
* [x] `decision-points.md`
* [x] `exception-pathways.md`
* [x] `content-quality-controls.md`
* [x] `pain-points-and-risks.md`
* [x] `omnichannel-implications.md`

### `02-customer-focus-information-support/sops/`

* [x] `CFIS-SOP-001-update-service-directory-content.md`
* [x] `CFIS-SOP-002-maintain-customer-service-tools.md`
* [x] `CFIS-SOP-003-support-crm-user-issues-and-requests.md`
* [x] `CFIS-SOP-004-maintain-telephone-messages-on-hold.md`
* [x] `CFIS-SOP-005-coordinate-hot-topic-customer-responses.md`
* [x] `CFIS-SOP-006-communicate-urgent-updates-to-branch-staff.md`
* [x] `CFIS-SOP-007-support-service-directory-editors.md`
* [x] `CFIS-SOP-008-improve-first-contact-resolution-content.md`

### `03-cross-function-learning/`

* [x] `common-patterns.md`
* [x] `shared-systems.md`
* [x] `shared-governance-gaps.md`
* [x] `shared-data-and-knowledge-dependencies.md`
* [x] `role-gap-and-capability-signals.md`
* [x] `automation-candidates.md`
* [x] `future-operating-model-signals.md`

### `04-templates/`

* [x] `sop-discovery-template.md`
* [x] `current-state-sop-template.md`
* [x] `pain-point-register-template.md`
* [x] `risk-register-template.md`
* [x] `assumptions-register-template.md`
* [x] `decision-log-template.md`
* [x] `evidence-register-template.md`
* [x] `stakeholder-interview-guide-template.md`
* [x] `system-inventory-template.md`
* [x] `source-of-truth-assessment-template.md`
* [x] `workflow-and-lifecycle-template.md`
* [x] `business-case-evidence-template.md`
* [x] `validation-checklist-template.md`

### `05-decisions/`

* [x] `ADR-001-map-actual-practice-not-aspirational-pd.md`
* [ ] `ADR-002-keep-functions-separated-during-current-state-discovery.md`
* [ ] `ADR-003-use-github-for-sop-discovery.md`
* [ ] `ADR-004-design-for-future-enterprise-migration.md`

---

## Next session starting point

Continue from:

`05-decisions/ADR-002-keep-functions-separated-during-current-state-discovery.md`

Recommended remaining order:

1. `05-decisions/ADR-002-keep-functions-separated-during-current-state-discovery.md`
2. `05-decisions/ADR-003-use-github-for-sop-discovery.md`
3. `05-decisions/ADR-004-design-for-future-enterprise-migration.md`
4. `01-customer-data-and-systems-support/current-state-process-map.md`
5. `02-customer-focus-information-support/current-state-process-map.md`
6. Optional remaining templates if still useful
